load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "config",
    srcs = ["config.go"],
    importpath = "github.com/bazelbuild/bazelisk/config",
    visibility = ["//visibility:public"],
    deps = [
        "//ws",
        "@com_github_mitchellh_go_homedir//:go_default_library",
    ],
)
