package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_sass//:defs.bzl", "sass_library")

sass_library(
    name = "settings",
    srcs = ["_settings.scss"],
    visibility = [
        "//third_party/foundation:__subpackages__",
    ],
    deps = [
        "//third_party/foundation/util",
    ],
)
