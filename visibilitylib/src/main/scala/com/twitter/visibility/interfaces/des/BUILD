scala_library(
    sources = ["*.scala"],
    compiler_option_sets = ["fatal_warnings"],
    strict_deps = True,
    tags = ["bazel-compatible"],
    dependencies = [
        "src/thrift/com/twitter/spam/rtf:tweet-rtf-event-scala",
        "src/thrift/com/twitter/tweetypie:events-scala",
        "src/thrift/com/twitter/tweetypie:tweet-scala",
        "stitch/stitch-core",
        "visibility/common/src/main/scala/com/twitter/visibility/common",
        "visibility/common/src/main/thrift/com/twitter/visibility:action-scala",
        "visibility/lib/src/main/resources/config",
        "visibility/lib/src/main/scala/com/twitter/visibility",
        "visibility/lib/src/main/scala/com/twitter/visibility/builder/tweets",
        "visibility/lib/src/main/scala/com/twitter/visibility/builder/users",
        "visibility/lib/src/main/scala/com/twitter/visibility/features",
        "visibility/lib/src/main/scala/com/twitter/visibility/interfaces/common/tweets",
    ],
    exports = [
        "visibility/lib/src/main/scala/com/twitter/visibility",
    ],
)
