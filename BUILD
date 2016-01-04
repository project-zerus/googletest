licenses(["notice"])

cc_library(
  name = "gtest",
  testonly = 1,
  visibility = ["//visibility:public"],
  includes = [
    "gtest-1.7.0/include",
  ],
  hdrs = [
    'gtest-1.7.0/include/gtest/gtest.h',
    'gtest-1.7.0/src/gtest-internal-inl.h',
    'gtest-1.7.0/src/gtest.cc',
    'gtest-1.7.0/src/gtest-death-test.cc',
    'gtest-1.7.0/src/gtest-filepath.cc',
    'gtest-1.7.0/src/gtest-port.cc',
    'gtest-1.7.0/src/gtest-printers.cc',
    'gtest-1.7.0/src/gtest-test-part.cc',
    'gtest-1.7.0/src/gtest-typed-test.cc',
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
