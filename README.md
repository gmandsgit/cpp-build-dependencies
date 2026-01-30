# C++ Build Dependencies

Prebuilt native C++ build dependencies used for development, CI, and Dockerized builds.

## Included
- gRPC (v1.66.1)
- AWS SDK for C++ (S3 only)

## Purpose
- Speed up CI
- Avoid rebuilding heavy native dependencies
- Ensure reproducible builds across platforms

## Disclaimer
This repository provides prebuilt binaries for convenience.
It is not an official SDK and is not affiliated with Google or AWS.