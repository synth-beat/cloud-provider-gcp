load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "gomega",
    srcs = [
        "gomega_dsl.go",
        "matchers.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/onsi/gomega",
    importpath = "github.com/onsi/gomega",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/google/go-cmp/cmp",
        "//vendor/github.com/onsi/gomega/internal",
        "//vendor/github.com/onsi/gomega/matchers",
        "//vendor/github.com/onsi/gomega/types",
    ],
)
