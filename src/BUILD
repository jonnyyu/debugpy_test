load("@pip_deps//:requirements.bzl", "requirement")
load("@rules_python//python:defs.bzl", "py_binary")

py_binary(
    name = "debugpy_test",
    srcs = ["main.py"],
    main = "main.py",
    deps = [
        requirement("debugpy")
    ]
)