load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "uuid",
    srcs = ["uuid.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apimachinery/pkg/util/uuid",
    importpath = "k8s.io/apimachinery/pkg/util/uuid",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/google/uuid",
        "//vendor/k8s.io/apimachinery/pkg/types",
    ],
)
