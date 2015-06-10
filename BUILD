licenses(["notice"])

cc_library(
  name = "gtest",
  testonly = 1,
  visibility = ["//visibility:public"],
  includes = [
    "gtest-1.7.0/include",
  ],
  srcs = [
    'gtest-1.7.0/src/gtest-all.cc',
  ],
  deps = [
    "//external:gflags",
  ],
  copts = [
    '-iquotegoogletest/gtest-1.7.0'
  ]
)

cc_library(
  name = "gtest_main",
  testonly = 1,
  visibility = ["//visibility:public"],
  deps = [
    ":gtest",
  ],
  srcs = [
    "gtest-1.7.0/src/gtest_main.cc",
  ],
)
