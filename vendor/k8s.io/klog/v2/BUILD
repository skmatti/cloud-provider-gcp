load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "klog",
    srcs = [
        "contextual.go",
        "exit.go",
        "imports.go",
        "k8s_references.go",
        "klog.go",
        "klog_file.go",
        "klog_file_others.go",
        "klog_file_windows.go",
        "klogr.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/klog/v2",
    importpath = "k8s.io/klog/v2",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/go-logr/logr",
        "//vendor/k8s.io/klog/v2/internal/buffer",
        "//vendor/k8s.io/klog/v2/internal/clock",
        "//vendor/k8s.io/klog/v2/internal/dbg",
        "//vendor/k8s.io/klog/v2/internal/serialize",
        "//vendor/k8s.io/klog/v2/internal/severity",
    ],
)
