package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_sass//:defs.bzl", "sass_binary", "sass_library")

sass_library(
    name = "normalize",
    srcs = [
        "normalize.scss",
    ],
    visibility = [
        "//third_party/foundation:__subpackages__",
    ],
)

sass_binary(
    name = "normalize_css",
    src = "normalize.scss",
)
