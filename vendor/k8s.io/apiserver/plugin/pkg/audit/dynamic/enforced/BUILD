load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["enforced.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apiserver/plugin/pkg/audit/dynamic/enforced",
    importpath = "k8s.io/apiserver/plugin/pkg/audit/dynamic/enforced",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/apiserver/pkg/apis/audit:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/audit:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/audit/event:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/audit/policy:go_default_library",
    ],
)
