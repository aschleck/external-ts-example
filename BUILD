package(default_visibility = ["//visibility:public"])

load("@aspect_rules_ts//ts:defs.bzl", "ts_config", "ts_project")

ts_config(
    name = "tsconfig",
    src = "tsconfig.json",
)

ts_project(
    name = "lib",
    srcs = ["test.ts"],
    deps = [
        "@dev_april_corgi//js/common",
    ],
)
