workspace(name = "trivial_go_repo")

http_archive(
    name = "io_bazel_rules_go",
    url = "https://codeload.github.com/bazelbuild/rules_go/zip/ee1fef7ec1379fcf36c002fd3ac0d00d940b147e",
    strip_prefix = "rules_go-ee1fef7ec1379fcf36c002fd3ac0d00d940b147e",
    type = "zip",
)
load("@io_bazel_rules_go//go:def.bzl", "go_rules_dependencies", "go_register_toolchains")

go_rules_dependencies()
go_register_toolchains()
