load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "propagation",
    srcs = ["propagation.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/go.opencensus.io/trace/propagation",
    importpath = "go.opencensus.io/trace/propagation",
    visibility = ["//visibility:public"],
    deps = ["//vendor/go.opencensus.io/trace"],
)
