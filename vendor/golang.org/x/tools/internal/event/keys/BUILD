load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "keys",
    srcs = [
        "keys.go",
        "standard.go",
        "util.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/golang.org/x/tools/internal/event/keys",
    importpath = "golang.org/x/tools/internal/event/keys",
    visibility = ["//vendor/golang.org/x/tools:__subpackages__"],
    deps = ["//vendor/golang.org/x/tools/internal/event/label"],
)
