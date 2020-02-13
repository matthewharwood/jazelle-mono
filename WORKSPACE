load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
http_archive(
  name = "jazelle",
  url = "https://registry.yarnpkg.com/jazelle/-/jazelle-0.0.0-alpha.9.tgz",
  strip_prefix = "package",
)

load("@jazelle//:workspace-rules.bzl", "jazelle_dependencies")
jazelle_dependencies(
  node_version = "10.16.3",
  node_sha256 = {
    "mac": "6febc571e1543c2845fa919c6d06b36a24e4e142c91aedbe28b6ff7d296119e4",
    "linux": "d2271fd8cf997fa7447d638dfa92749ff18ca4b0d796bf89f2a82bf7800d5506",
    "windows": "19aa47de7c5950d7bd71a1e878013b98d93871cc311d7185f5472e6d3f633146",
  },
  yarn_version = "1.19.1",
  yarn_sha256 = "fdbc534294caef9cc0d7384fb579ec758da7fc033392ce54e0e8268e4db24baf",
)
