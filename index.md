---
layout: default
---
 OpenScanHub is a service that runs various static analyzers on RPM packages. The tasks can be triggered by users from the command-line interface provided by the osh-client RPM package. The client can be invoked interactively as well as from CI environments and other automation.

OpenScanHub by default uses Cppcheck, ShellCheck, the static analyzers embedded in GCC and Clang, and the find-unicode-control tool. Other tools for static (and dynamic) analysis can be enabled on demand while submitting an OpenScanHub task.

OpenScanHub is not limited to RPM packages. It can also statically analyze upstream tarballs and OpenShift containers.
