licenses(["notice"])  # Apache 2

exports_files([
    "EnvoyEngine.h",
])

objc_library(
    name = "envoy_engine_objc_lib",
    srcs = [
        "EnvoyConfiguration.m",
        "EnvoyEngineImpl.m",
        "EnvoyHTTPCallbacks.m",
        "EnvoyHTTPStreamImpl.m",
        "EnvoyNetworkMonitor.m",
    ],
    hdrs = [
        "EnvoyEngine.h",
    ],
    sdk_frameworks = [
        "SystemConfiguration",
    ],
    visibility = ["//visibility:public"],
    deps = ["//library/common:envoy_main_interface_lib"],
)
