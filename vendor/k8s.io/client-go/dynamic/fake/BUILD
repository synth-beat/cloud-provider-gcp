load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "fake",
    srcs = ["simple.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/dynamic/fake",
    importpath = "k8s.io/client-go/dynamic/fake",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/apimachinery/pkg/api/meta",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured",
        "//vendor/k8s.io/apimachinery/pkg/labels",
        "//vendor/k8s.io/apimachinery/pkg/runtime",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema",
        "//vendor/k8s.io/apimachinery/pkg/runtime/serializer",
        "//vendor/k8s.io/apimachinery/pkg/types",
        "//vendor/k8s.io/apimachinery/pkg/watch",
        "//vendor/k8s.io/client-go/dynamic",
        "//vendor/k8s.io/client-go/testing",
    ],
)
