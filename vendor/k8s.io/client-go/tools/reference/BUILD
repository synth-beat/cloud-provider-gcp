load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "reference",
    srcs = ["ref.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/tools/reference",
    importpath = "k8s.io/client-go/tools/reference",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/core/v1:core",
        "//vendor/k8s.io/apimachinery/pkg/api/meta",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/runtime",
    ],
)
