load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "extensions",
    srcs = ["interface.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/informers/extensions",
    importpath = "k8s.io/client-go/informers/extensions",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/client-go/informers/extensions/v1beta1",
        "//vendor/k8s.io/client-go/informers/internalinterfaces",
    ],
)
