load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "register",
    srcs = ["register.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/controller-manager/pkg/features/register",
    importpath = "k8s.io/controller-manager/pkg/features/register",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/apimachinery/pkg/util/runtime",
        "//vendor/k8s.io/apiserver/pkg/util/feature",
        "//vendor/k8s.io/controller-manager/pkg/features",
    ],
)
