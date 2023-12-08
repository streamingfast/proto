# Change log

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 2023-12-08

## Removed

* Removed sf.bstream.v1 -> it now lives inside github.com/streamingfast/bstream

## 2022-02-28

### Removed

- **BREAKING CHANGE** The well-known types definitions have been removed, newer version of `protoc` have them embedded removing the need to have them referenced explicitely here.

- **BREAKING CHANGE** The `grpc.health.v1.health.proto` file has been removed, use https://github.com/grpc/grpc/blob/master/src/proto/grpc/health/v1/health.proto instead (library for various languages now exists for the actual generated code).
