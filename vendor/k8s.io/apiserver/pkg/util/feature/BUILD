load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "feature",
    srcs = ["feature_gate.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apiserver/pkg/util/feature",
    importpath = "k8s.io/apiserver/pkg/util/feature",
    visibility = ["//visibility:public"],
    deps = ["//vendor/k8s.io/component-base/featuregate"],
)
