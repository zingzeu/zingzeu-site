package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_sass//:defs.bzl", "sass_library")

sass_library(
    name = "typography",
    srcs = glob(["_*.scss"]),
    visibility = [
        "//third_party/foundation:__subpackages__",
    ],
)
