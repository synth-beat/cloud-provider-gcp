load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "appengine",
    srcs = [
        "appengine.go",
        "appengine_vm.go",
        "errors.go",
        "identity.go",
        "namespace.go",
        "timeout.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/appengine",
    importpath = "google.golang.org/appengine",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/golang/protobuf/proto",
        "//vendor/golang.org/x/net/context",
        "//vendor/google.golang.org/appengine/internal",
        "//vendor/google.golang.org/appengine/internal/app_identity",
        "//vendor/google.golang.org/appengine/internal/modules",
    ],
)
