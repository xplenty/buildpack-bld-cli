# Build.io CLI CNB Buildpack

This is a Cloud Native Buildpack (CNB) for [Build.io](https://build.io) that installs the Build.io CLI in containerized environments.

## Overview

This buildpack automatically downloads and installs the latest Build.io CLI binary from the [buildio/cli releases](https://github.com/buildio/cli/releases). The CLI binary is a fully static Linux build created using Alpine Linux, ensuring compatibility across different container environments.
