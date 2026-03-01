load("@rules_cc//cc:defs.bzl", "cc_binary")

package(default_visibility = ["//visibility:private"])

cc_binary(
    name = "example_new",
    srcs = ["example.cc"],
    visibility = [
        "//visibility:public",
    ],
    deps = [
        "@abseil-cpp//absl/container:flat_hash_set",
        "@phtree-cpp//:phtree",
    ],
)
