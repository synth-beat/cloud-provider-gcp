load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "apps",
    srcs = [
        "controllerrevision.go",
        "daemonset.go",
        "deployment.go",
        "interface.go",
        "replicaset.go",
        "statefulset.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/informers/apps/v1",
    importpath = "k8s.io/client-go/informers/apps/v1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/apps/v1:apps",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/runtime",
        "//vendor/k8s.io/apimachinery/pkg/watch",
        "//vendor/k8s.io/client-go/informers/internalinterfaces",
        "//vendor/k8s.io/client-go/kubernetes",
        "//vendor/k8s.io/client-go/listers/apps/v1:apps",
        "//vendor/k8s.io/client-go/tools/cache",
    ],
)
