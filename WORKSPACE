load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "io_bazel_rules_sass",
    # Make sure to check for the latest version when you install
    url = "https://github.com/bazelbuild/rules_sass/archive/1.22.7.zip",
    strip_prefix = "rules_sass-1.22.7",
    sha256 = "a8b6d287a5d40d70662c4d6a1db282e9f3d34a0cf6acd091dfb4c85c9f7c6997",
)

# Fetch required transitive dependencies. This is an optional step because you
# can always fetch the required NodeJS transitive dependency on your own.
load("@io_bazel_rules_sass//:package.bzl", "rules_sass_dependencies")
rules_sass_dependencies()

# Setup repositories which are needed for the Sass rules.
load("@io_bazel_rules_sass//:defs.bzl", "sass_repositories")
sass_repositories()