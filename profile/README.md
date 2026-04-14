# SindarinSDK

The Sindarin programming language and ecosystem.

Documentation: https://sindarinsdk.github.io/

## Build status

### Core
| Repository | Description | CI | Release |
|------------|-------------|----|---------|
| [sindarin-compiler](https://github.com/SindarinSDK/sindarin-compiler) | Language compiler (`sn`) | [![Compiler](https://github.com/SindarinSDK/sindarin-compiler/actions/workflows/ci.yml/badge.svg)](https://github.com/SindarinSDK/sindarin-compiler/actions/workflows/ci.yml) | [![Release](https://github.com/SindarinSDK/sindarin-compiler/actions/workflows/release.yml/badge.svg?event=push)](https://github.com/SindarinSDK/sindarin-compiler/actions/workflows/release.yml) |
| [sindarin-pkg-sdk](https://github.com/SindarinSDK/sindarin-pkg-sdk) | Standard library | [![SDK](https://github.com/SindarinSDK/sindarin-pkg-sdk/actions/workflows/ci.yml/badge.svg)](https://github.com/SindarinSDK/sindarin-pkg-sdk/actions/workflows/ci.yml) | — |
| [sindarin-pkg-test](https://github.com/SindarinSDK/sindarin-pkg-test) | Test framework | [![Test](https://github.com/SindarinSDK/sindarin-pkg-test/actions/workflows/ci.yml/badge.svg)](https://github.com/SindarinSDK/sindarin-pkg-test/actions/workflows/ci.yml) | — |
| [sindarin-pkg-libs](https://github.com/SindarinSDK/sindarin-pkg-libs) | Prebuilt native binaries (linux/macos/windows) | — | [![Release](https://github.com/SindarinSDK/sindarin-pkg-libs/actions/workflows/release.yml/badge.svg?event=push)](https://github.com/SindarinSDK/sindarin-pkg-libs/actions/workflows/release.yml) |

### Language packages
| Repository | Description | CI |
|------------|-------------|----|
| [sindarin-pkg-collections](https://github.com/SindarinSDK/sindarin-pkg-collections) | Data structures | [![Collections](https://github.com/SindarinSDK/sindarin-pkg-collections/actions/workflows/ci.yml/badge.svg)](https://github.com/SindarinSDK/sindarin-pkg-collections/actions/workflows/ci.yml) |
| [sindarin-pkg-threads](https://github.com/SindarinSDK/sindarin-pkg-threads) | Threads, pools, mutexes, locks | [![Threads](https://github.com/SindarinSDK/sindarin-pkg-threads/actions/workflows/ci.yml/badge.svg)](https://github.com/SindarinSDK/sindarin-pkg-threads/actions/workflows/ci.yml) |
| [sindarin-pkg-json](https://github.com/SindarinSDK/sindarin-pkg-json) | JSON parser (pure Sindarin) | [![JSON](https://github.com/SindarinSDK/sindarin-pkg-json/actions/workflows/ci.yml/badge.svg)](https://github.com/SindarinSDK/sindarin-pkg-json/actions/workflows/ci.yml) |
| [sindarin-pkg-yaml](https://github.com/SindarinSDK/sindarin-pkg-yaml) | YAML encoder/decoder | [![YAML](https://github.com/SindarinSDK/sindarin-pkg-yaml/actions/workflows/ci.yml/badge.svg)](https://github.com/SindarinSDK/sindarin-pkg-yaml/actions/workflows/ci.yml) |
| [sindarin-pkg-logging](https://github.com/SindarinSDK/sindarin-pkg-logging) | Logging | [![Logging](https://github.com/SindarinSDK/sindarin-pkg-logging/actions/workflows/ci.yml/badge.svg)](https://github.com/SindarinSDK/sindarin-pkg-logging/actions/workflows/ci.yml) |

### Network
| Repository | Description | CI | Release |
|------------|-------------|----|---------|
| [sindarin-pkg-http](https://github.com/SindarinSDK/sindarin-pkg-http) | HTTP server | [![HTTP](https://github.com/SindarinSDK/sindarin-pkg-http/actions/workflows/ci.yml/badge.svg)](https://github.com/SindarinSDK/sindarin-pkg-http/actions/workflows/ci.yml) | — |
| [sindarin-pkg-curl](https://github.com/SindarinSDK/sindarin-pkg-curl) | HTTP client | [![cURL](https://github.com/SindarinSDK/sindarin-pkg-curl/actions/workflows/ci.yml/badge.svg)](https://github.com/SindarinSDK/sindarin-pkg-curl/actions/workflows/ci.yml) | [![Release](https://github.com/SindarinSDK/sindarin-pkg-curl/actions/workflows/release.yml/badge.svg?event=push)](https://github.com/SindarinSDK/sindarin-pkg-curl/actions/workflows/release.yml) |
| [sindarin-pkg-net-quic](https://github.com/SindarinSDK/sindarin-pkg-net-quic) | QUIC protocol | [![QUIC](https://github.com/SindarinSDK/sindarin-pkg-net-quic/actions/workflows/ci.yml/badge.svg)](https://github.com/SindarinSDK/sindarin-pkg-net-quic/actions/workflows/ci.yml) | [![Release](https://github.com/SindarinSDK/sindarin-pkg-net-quic/actions/workflows/release.yml/badge.svg?event=push)](https://github.com/SindarinSDK/sindarin-pkg-net-quic/actions/workflows/release.yml) |

### Databases
| Repository | Description | CI | Release |
|------------|-------------|----|---------|
| [sindarin-pkg-sqlite](https://github.com/SindarinSDK/sindarin-pkg-sqlite) | SQLite driver | [![SQLite](https://github.com/SindarinSDK/sindarin-pkg-sqlite/actions/workflows/ci.yml/badge.svg)](https://github.com/SindarinSDK/sindarin-pkg-sqlite/actions/workflows/ci.yml) | [![Release](https://github.com/SindarinSDK/sindarin-pkg-sqlite/actions/workflows/release.yml/badge.svg?event=push)](https://github.com/SindarinSDK/sindarin-pkg-sqlite/actions/workflows/release.yml) |
| [sindarin-pkg-postgres](https://github.com/SindarinSDK/sindarin-pkg-postgres) | PostgreSQL driver | [![PostgreSQL](https://github.com/SindarinSDK/sindarin-pkg-postgres/actions/workflows/ci.yml/badge.svg)](https://github.com/SindarinSDK/sindarin-pkg-postgres/actions/workflows/ci.yml) | [![Release](https://github.com/SindarinSDK/sindarin-pkg-postgres/actions/workflows/release.yml/badge.svg?event=push)](https://github.com/SindarinSDK/sindarin-pkg-postgres/actions/workflows/release.yml) |
| [sindarin-pkg-mysql](https://github.com/SindarinSDK/sindarin-pkg-mysql) | MySQL driver | [![MySQL](https://github.com/SindarinSDK/sindarin-pkg-mysql/actions/workflows/ci.yml/badge.svg)](https://github.com/SindarinSDK/sindarin-pkg-mysql/actions/workflows/ci.yml) | [![Release](https://github.com/SindarinSDK/sindarin-pkg-mysql/actions/workflows/release.yml/badge.svg?event=push)](https://github.com/SindarinSDK/sindarin-pkg-mysql/actions/workflows/release.yml) |
| [sindarin-pkg-mongo](https://github.com/SindarinSDK/sindarin-pkg-mongo) | MongoDB client | [![MongoDB](https://github.com/SindarinSDK/sindarin-pkg-mongo/actions/workflows/ci.yml/badge.svg)](https://github.com/SindarinSDK/sindarin-pkg-mongo/actions/workflows/ci.yml) | [![Release](https://github.com/SindarinSDK/sindarin-pkg-mongo/actions/workflows/release.yml/badge.svg?event=push)](https://github.com/SindarinSDK/sindarin-pkg-mongo/actions/workflows/release.yml) |
| [sindarin-pkg-sqlserver](https://github.com/SindarinSDK/sindarin-pkg-sqlserver) | SQL Server driver | [![SQL Server](https://github.com/SindarinSDK/sindarin-pkg-sqlserver/actions/workflows/ci.yml/badge.svg)](https://github.com/SindarinSDK/sindarin-pkg-sqlserver/actions/workflows/ci.yml) | [![Release](https://github.com/SindarinSDK/sindarin-pkg-sqlserver/actions/workflows/release.yml/badge.svg?event=push)](https://github.com/SindarinSDK/sindarin-pkg-sqlserver/actions/workflows/release.yml) |

### Machine learning
| Repository | Description | CI | Release |
|------------|-------------|----|---------|
| [sindarin-pkg-tensor](https://github.com/SindarinSDK/sindarin-pkg-tensor) | Tensor / ML primitives | [![Tensor](https://github.com/SindarinSDK/sindarin-pkg-tensor/actions/workflows/ci.yml/badge.svg)](https://github.com/SindarinSDK/sindarin-pkg-tensor/actions/workflows/ci.yml) | [![Release](https://github.com/SindarinSDK/sindarin-pkg-tensor/actions/workflows/release.yml/badge.svg?event=push)](https://github.com/SindarinSDK/sindarin-pkg-tensor/actions/workflows/release.yml) |

### Tooling & infrastructure
| Repository | Description | Status |
|------------|-------------|--------|
| [sindarin-pipelines](https://github.com/SindarinSDK/sindarin-pipelines) | Reusable CI pipelines | [![Pkg Test](https://github.com/SindarinSDK/sindarin-pipelines/actions/workflows/sindarin-pkg-test.yml/badge.svg)](https://github.com/SindarinSDK/sindarin-pipelines/actions/workflows/sindarin-pkg-test.yml) [![Lib Release](https://github.com/SindarinSDK/sindarin-pipelines/actions/workflows/sindarin-lib-release.yml/badge.svg?event=push)](https://github.com/SindarinSDK/sindarin-pipelines/actions/workflows/sindarin-lib-release.yml) |
| [sindarin-template](https://github.com/SindarinSDK/sindarin-template) | Project template | [![CI](https://github.com/SindarinSDK/sindarin-template/actions/workflows/ci.yml/badge.svg)](https://github.com/SindarinSDK/sindarin-template/actions/workflows/ci.yml) |
