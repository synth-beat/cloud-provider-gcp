load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "net",
    srcs = [
        "http.go",
        "interface.go",
        "port_range.go",
        "port_split.go",
        "util.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apimachinery/pkg/util/net",
    importpath = "k8s.io/apimachinery/pkg/util/net",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/golang.org/x/net/http2",
        "//vendor/k8s.io/apimachinery/pkg/util/sets",
        "//vendor/k8s.io/klog/v2:klog",
        "//vendor/k8s.io/utils/net",
    ],
)
