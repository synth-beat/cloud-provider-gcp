load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "latest",
    srcs = ["latest.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/tools/clientcmd/api/latest",
    importpath = "k8s.io/client-go/tools/clientcmd/api/latest",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/apimachinery/pkg/runtime",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema",
        "//vendor/k8s.io/apimachinery/pkg/runtime/serializer/json",
        "//vendor/k8s.io/apimachinery/pkg/runtime/serializer/versioning",
        "//vendor/k8s.io/apimachinery/pkg/util/runtime",
        "//vendor/k8s.io/client-go/tools/clientcmd/api",
        "//vendor/k8s.io/client-go/tools/clientcmd/api/v1:api",
    ],
)
