objc_binary(
    name = "Multisport",
    srcs = [
        "Multisport/main.m",
    ],
    infoplist = "Multisport/Multisport-Info.plist",
    visibility = ["//visibility:public"],
    deps = [
        ":MultisportClasses",
    ],
)

objc_library(
    name = "MultisportClasses",
    srcs = glob(["**/*.m"]),
    hdrs = glob(["**/*.h"]),
    sdk_frameworks = ["UIKit"],
)
