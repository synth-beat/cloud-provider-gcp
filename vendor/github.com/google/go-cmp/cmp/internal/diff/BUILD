load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "diff",
    srcs = [
        "debug_disable.go",
        "diff.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/google/go-cmp/cmp/internal/diff",
    importpath = "github.com/google/go-cmp/cmp/internal/diff",
    visibility = ["//vendor/github.com/google/go-cmp/cmp:__subpackages__"],
    deps = ["//vendor/github.com/google/go-cmp/cmp/internal/flags"],
)
