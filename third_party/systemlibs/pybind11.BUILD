package(default_visibility = ["//visibility:public"])

cc_library(
    name = "pybind11",
    deps = [
        "@org_tensorflow//third_party/python_runtime:headers",
    ],
)

# Needed by pybind11_bazel.
config_setting(
    name = "osx",
    constraint_values = ["@platforms//os:osx"],
)
