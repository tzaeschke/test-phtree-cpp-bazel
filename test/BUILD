load("@rules_cc//cc:defs.bzl", "cc_test")

package(default_visibility = ["//visibility:private"])

cc_test(
    name = "phtree_test",
    timeout = "long",
    srcs = [
        "phtree_test.cc",
    ],
    linkstatic = True,
    deps = [
        "@googletest//:gtest_main",
        "@phtree-cpp//:phtree",
    ],
)

cc_test(
    name = "phtree_multimap_box_d_test",
    timeout = "long",
    srcs = [
        "phtree_multimap_box_d_test.cc",
    ],
    linkstatic = True,
    deps = [
        "@googletest//:gtest_main",
        "@phtree-cpp//:phtree",
    ],
)
