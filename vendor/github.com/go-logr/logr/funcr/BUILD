load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "funcr",
    srcs = ["funcr.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/go-logr/logr/funcr",
    importpath = "github.com/go-logr/logr/funcr",
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/go-logr/logr"],
)
