load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "format",
    srcs = [
        "format.go",
        "parser.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/golang.org/x/text/internal/format",
    importpath = "golang.org/x/text/internal/format",
    visibility = ["//vendor/golang.org/x/text:__subpackages__"],
    deps = ["//vendor/golang.org/x/text/language"],
)
