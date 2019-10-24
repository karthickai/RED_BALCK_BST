
load("@rules_cc//cc:defs.bzl", "cc_binary", "cc_library")

cc_library(
    name = "red_black_bst_lib",
    srcs = ["red_black_bst.cc"],
    hdrs = ["red_black_bst.hpp"],
)

cc_binary(
    name = "red_black_bst",
    srcs = ["main.cc"],
    deps = [
        ":red_black_bst_lib",
    ],
)