workspace(name = "main")

load("@bazel_tools//tools/build_defs/repo:java.bzl", "java_import_external")

java_import_external(
    name = "com_google_guava_guava",
    licenses = ["notice"],  # Apache 2.0
    jar_urls = [
        "http://bazel-mirror.storage.googleapis.com/repo1.maven.org/maven2/com/google/guava/guava/20.0/guava-20.0.jar",
        "http://repo1.maven.org/maven2/com/google/guava/guava/20.0/guava-20.0.jar",
        "http://maven.ibiblio.org/maven2/com/google/guava/guava/20.0/guava-20.0.jar",
    ],
    jar_sha256 = "36a666e3b71ae7f0f0dca23654b67e086e6c93d192f60ba5dfd5519db6c288c8",
    deps = [
        "@com_google_code_findbugs_jsr305",
        "@com_google_errorprone_error_prone_annotations",
    ],
)
java_import_external(
    name = "com_google_code_findbugs_jsr305",
    licenses = ["notice"],  # BSD 3-clause
    jar_urls = [
        "http://bazel-mirror.storage.googleapis.com/repo1.maven.org/maven2/com/google/code/findbugs/jsr305/1.3.9/jsr305-1.3.9.jar",
        "http://repo1.maven.org/maven2/com/google/code/findbugs/jsr305/1.3.9/jsr305-1.3.9.jar",
        "http://maven.ibiblio.org/maven2/com/google/code/findbugs/jsr305/1.3.9/jsr305-1.3.9.jar",
    ],
    jar_sha256 = "905721a0eea90a81534abb7ee6ef4ea2e5e645fa1def0a5cd88402df1b46c9ed",
)
java_import_external(
    name = "com_google_errorprone_error_prone_annotations",
    licenses = ["notice"],  # Apache 2.0
    jar_sha256 = "e7749ffdf03fb8ebe08a727ea205acb301c8791da837fee211b99b04f9d79c46",
    jar_urls = [
        "http://bazel-mirror.storage.googleapis.com/repo1.maven.org/maven2/com/google/errorprone/error_prone_annotations/2.0.15/error_prone_annotations-2.0.15.jar",
        "http://maven.ibiblio.org/maven2/com/google/errorprone/error_prone_annotations/2.0.15/error_prone_annotations-2.0.15.jar",
        "http://repo1.maven.org/maven2/com/google/errorprone/error_prone_annotations/2.0.15/error_prone_annotations-2.0.15.jar",
    ],
)
java_import_external(
        name = "google_java_format",
        licenses = ["notice"],  # Apache 2.0
        jar_urls = [
            "https://github.com/google/google-java-format/releases/download/google-java-format-1.5/google-java-format-1.5-all-deps.jar",
        ],
        jar_sha256 = ("7b839bb7534a173f0ed0cd0e9a583181d20850fcec8cf6e3800e4420a1fad184"),
)