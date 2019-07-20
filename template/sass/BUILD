package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_sass//:defs.bzl", "sass_binary","sass_library")

sass_binary(
    name ="site",
    src = "site.scss",
    deps = [
        ":settings",
        "//third_party/foundation"
    ]
)

sass_library(
    name = "settings",
    srcs = ["_settings.scss"],
    deps = [
        "//third_party/foundation/util"
    ]
)