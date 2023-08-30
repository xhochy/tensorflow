load("@rules_cc//cc:defs.bzl", "cc_library")

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "log",
    linkopts = [
        "-labsl_log_internal_conditions",
        "-labsl_log_internal_check_op",
        "-labsl_log_internal_message",
        "-labsl_log_internal_nullguard",
    ],
)

cc_library(
    name = "check",
    linkopts = [
        "-labsl_log_internal_check_op",
        "-labsl_log_internal_message",
        "-labsl_log_internal_nullguard",
    ],
)
