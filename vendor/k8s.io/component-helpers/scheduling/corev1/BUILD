load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "corev1",
    srcs = [
        "doc.go",
        "helpers.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/component-helpers/scheduling/corev1",
    importpath = "k8s.io/component-helpers/scheduling/corev1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/core/v1:core",
        "//vendor/k8s.io/component-helpers/scheduling/corev1/nodeaffinity",
    ],
)
