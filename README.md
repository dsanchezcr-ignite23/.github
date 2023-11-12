# Introduction

In this repository we are storing all the workflows that will be shared across the organization. In the organization settings we can define which of the jobs will be required to run in order to merge a pull request by defining status checks in the rulesets.

This is a great use case when you have a common group of repositories and you want to enable a common workflow across all of them.

In this case, we have one workflow called [build-codeql-net8.yml](/.github/workflows/build-codeql-net8.yml) with two jobs: `build` and `codeql-analysis`. The first one will build the .NET 8 apps and the second one will run a codeql analysis.