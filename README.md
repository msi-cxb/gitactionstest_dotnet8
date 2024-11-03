# gitactionstest_dotnet8 #

[![Validation of Console App](https://github.com/msi-cxb/gitactionstest_dotnet8/actions/workflows/CI.yml/badge.svg)](https://github.com/msi-cxb/gitactionstest_dotnet8/actions/workflows/CI.yml)

A repo to demo Github actions for Windows and .NET8

- CI.yml builds a sample .NET8 console app and runs MSTest unit tests.
- release.yml uses publish to build a standalone executable.
  - When a tag is set, the published executable will be added to Releases under the tag name.


