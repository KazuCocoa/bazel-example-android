git_repository(
    name = "org_pubref_rules_kotlin",
    remote = "https://github.com/pubref/rules_kotlin.git",
    tag = "v0.5.0",
)

load("@org_pubref_rules_kotlin//kotlin:rules.bzl", "kotlin_repositories")

kotlin_repositories()

android_sdk_repository(
    name = "androidsdk",
    path = "/Users/kazuaki/Library/Android/sdk",
    api_level = 26,
    build_tools_version = "26.0.1"
)
