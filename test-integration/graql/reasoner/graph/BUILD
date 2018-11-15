java_library(
    name = "diagonal-graph",
    srcs = ["DiagonalGraph.java"],
    deps = ["//server"],
    visibility = ["//test-integration:__subpackages__"],
    resources = ["//test-integration/graql/reasoner/resources:diagonal-test"]
)
java_library(
    name = "geo-graph",
    srcs = ["GeoGraph.java"],
    deps = ["//server"],
    visibility = ["//test-integration:__subpackages__"],
)
java_library(
    name = "linear-transitivity-matrix-graph",
    srcs = ["LinearTransitivityMatrixGraph.java"],
    deps = ["//server"],
    visibility = ["//test-integration:__subpackages__"],
    resources = ["//test-integration/graql/reasoner/resources:linear-transivity"]
)
java_library(
    name = "path-tree-graph",
    srcs = ["PathTreeGraph.java"],
    deps = ["//server", "//dependencies/maven/artifacts/com/google/guava:guava"],
    visibility = ["//test-integration:__subpackages__"],
    resources = ["//test-integration/graql/reasoner/resources:path-test"]
)
java_library(
    name = "transitivity-chain-graph",
    srcs = ["TransitivityChainGraph.java"],
    deps = ["//server"],
    visibility = ["//test-integration:__subpackages__"],
    resources = ["//test-integration/graql/reasoner/resources:quadratic-transitivity"]
)
java_library(
    name = "transitivity-matrix-graph",
    srcs = ["TransitivityMatrixGraph.java"],
    deps = ["//server"],
    visibility = ["//test-integration:__subpackages__"],
    resources = ["//test-integration/graql/reasoner/resources:quadratic-transitivity"]
)