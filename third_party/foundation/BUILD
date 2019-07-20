package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_sass//:defs.bzl", "sass_binary", "sass_library")

sass_library(
    name = "foundation",
    srcs = ["foundation.scss"],
    deps = [
        ":global",
        "//third_party/foundation/components",
        "//third_party/foundation/forms",
        "//third_party/foundation/grid",
        "//third_party/foundation/prototype",
        "//third_party/foundation/typography",
        "//third_party/foundation/util",
        "//third_party/foundation/settings",
        "//third_party/foundation/vendor:normalize",
        "//third_party/foundation/xy-grid",
        "//third_party/sassy-lists",
    ],
)

sass_library(
    name = "global",
    srcs = [
        "_global.scss",
    ],
    deps = [
        "//third_party/foundation/util",
        "//third_party/foundation/vendor:normalize",
    ],
)
