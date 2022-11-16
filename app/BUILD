load("@rules_android//android:rules.bzl", "android_binary")

android_binary(
    name = "bin",
    custom_package = "app.src.com.pete.restaurantbazel",
    manifest = "AndroidManifest.xml",
    manifest_values = {
        "minSdkVersion": "21",
        "targetSdkVersion": "29",
    },
    srcs = ["src/com/pete/restaurantbazel/MainActivity.java"],
    resource_files = glob(["res/**"]),
)