load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "group",
    srcs = [
        "authenticated_group_adder.go",
        "group_adder.go",
        "token_group_adder.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apiserver/pkg/authentication/group",
    importpath = "k8s.io/apiserver/pkg/authentication/group",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/apiserver/pkg/authentication/authenticator",
        "//vendor/k8s.io/apiserver/pkg/authentication/user",
    ],
)
