---
layout: custom
---
OpenScanHub is a service for static and dynamic analysis. By default it uses `Cppcheck`, `ShellCheck`, the static analyzers embedded in GCC and Clang, `find-unicode-control`, and the `Gitleaks` tool. Other tools for static (and dynamic) analysis can be enabled on demand while submitting an OpenScanHub scan.

By default it can analyze RPM packages, tarballs and OpenShift containers.

## Key Features

- It can perform differential scans i.e. compare newer version of a package with older version and report defects that were introduced in the newer version.
- It is extensible through plugins and can scan any type of source code.
- It can collect reports from various analyzers in a single place.

## Who uses it?

It has been used inside Red Hat to scan releases of RHEL and few other projects.

## Developers

Developer documentation can be found on [GitHub](https://github.com/openscanhub/openscanhub/blob/main/docs/development.md).

## Related Links

Code Scanning Utilities - [csutils](https://github.com/csutils)

## Contacts

If you have any questions you can open an issue on [GitHub](https://github.com/openscanhub/openscanhub/issues/new).
