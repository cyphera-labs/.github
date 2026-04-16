# Cyphera

**Protect structured data wherever it lives.**

Open source data protection — cross-language SDKs and native database integrations. Format-preserving encryption that fits your existing columns, schemas, and workflows.

## SDKs

| Language | Package | Install |
|----------|---------|---------|
| [Java](https://github.com/cyphera-labs/cyphera-java) | [![Maven Central](https://img.shields.io/maven-central/v/io.cyphera/cyphera)](https://central.sonatype.com/artifact/io.cyphera/cyphera) | `io.cyphera:cyphera` |
| [Rust](https://github.com/cyphera-labs/cyphera-rust) | [![crates.io](https://img.shields.io/crates/v/cyphera)](https://crates.io/crates/cyphera) | `cyphera` |
| [Go](https://github.com/cyphera-labs/cyphera-go) | [![Go](https://img.shields.io/badge/go-pkg-blue)](https://pkg.go.dev/github.com/cyphera-labs/cyphera-go) | `go get github.com/cyphera-labs/cyphera-go` |
| [Python](https://github.com/cyphera-labs/cyphera-python) | [![PyPI](https://img.shields.io/pypi/v/cyphera)](https://pypi.org/project/cyphera/) | `pip install cyphera` |
| [Node.js](https://github.com/cyphera-labs/cyphera-node) | [![npm](https://img.shields.io/npm/v/cyphera)](https://www.npmjs.com/package/cyphera) | `npm install cyphera` |
| [.NET](https://github.com/cyphera-labs/cyphera-dotnet) | [![NuGet](https://img.shields.io/nuget/v/Cyphera)](https://www.nuget.org/packages/Cyphera) | `dotnet add package Cyphera` |
| [PHP](https://github.com/cyphera-labs/cyphera-php) | [![Packagist](https://img.shields.io/packagist/v/cyphera/cyphera)](https://packagist.org/packages/cyphera/cyphera) | `composer require cyphera/cyphera` |
| [Ruby](https://github.com/cyphera-labs/cyphera-ruby) | [![Gem](https://img.shields.io/gem/v/cyphera)](https://rubygems.org/gems/cyphera) | `gem install cyphera` |
| [Swift](https://github.com/cyphera-labs/cyphera-swift) | [![SPI](https://img.shields.io/endpoint?url=https%3A%2F%2Fswiftpackageindex.com%2Fapi%2Fpackages%2Fcyphera-labs%2Fcyphera-swift%2Fbadge%3Ftype%3Dswift-versions)](https://swiftpackageindex.com/cyphera-labs/cyphera-swift) | `.package(url: "...cyphera-swift.git")` |

## Integrations

| Platform | Repo | Type | Powered By | SDK Version |
|----------|------|------|------------|-------------|
| [Trino](https://github.com/cyphera-labs/cyphera-trino) | cyphera-trino | SQL UDF plugin | cyphera-java | 0.0.1-alpha.3 |
| [PostgreSQL](https://github.com/cyphera-labs/cyphera-postgres) | cyphera-postgres | Native extension (pgrx) | cyphera-rust | 0.0.1-alpha.1 |
| [Snowflake](https://github.com/cyphera-labs/cyphera-snowflake) | cyphera-snowflake | Java UDF | cyphera-java | 0.0.1-alpha.3 |
| [Databricks](https://github.com/cyphera-labs/cyphera-databricks) | cyphera-databricks | Spark UDF | cyphera-java | 0.0.1-alpha.3 |
| [BigQuery](https://github.com/cyphera-labs/cyphera-bq) | cyphera-bq | Remote UDF | cyphera-go | not wired |
| [Informatica](https://github.com/cyphera-labs/cyphera-informatica) | cyphera-informatica | Java transformation | cyphera-java | 0.0.1-alpha.3 |
| [Striim](https://github.com/cyphera-labs/cyphera-striim) | cyphera-striim | UDF + Open Processor | cyphera-java | 0.0.1-alpha.3 |
| [Kafka Connect](https://github.com/cyphera-labs/cyphera-kafka-connect) | cyphera-kafka-connect | SMT (Single Message Transform) | cyphera-java | 0.0.1-alpha.3 |
| [Hibernate](https://github.com/cyphera-labs/cyphera-hibernate) | cyphera-hibernate | @CypheraProtect annotation | cyphera-java | 0.0.1-alpha.3 |
| [Apache NiFi](https://github.com/cyphera-labs/cyphera-nifi) | cyphera-nifi | NiFi Processor | cyphera-java | 0.0.1-alpha.3 |
| [Apache Flink](https://github.com/cyphera-labs/cyphera-flink) | cyphera-flink | Flink SQL UDF | cyphera-java | 0.0.1-alpha.3 |
| [StreamSets](https://github.com/cyphera-labs/cyphera-streamsets) | cyphera-streamsets | StreamSets Processor | cyphera-java | 0.0.1-alpha.3 |
| [Spring Boot](https://github.com/cyphera-labs/cyphera-spring) | cyphera-spring | Auto-configured starter | cyphera-java | 0.0.1-alpha.3 |

## Build Status

### SDKs
| | CI | Security |
|---|---|---|
| Java | [![CI](https://github.com/cyphera-labs/cyphera-java/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-java/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-java/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-java/actions/workflows/codeql.yml) |
| Rust | [![CI](https://github.com/cyphera-labs/cyphera-rust/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-rust/actions/workflows/ci.yml) | [![Security](https://github.com/cyphera-labs/cyphera-rust/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-rust/actions/workflows/codeql.yml) |
| Go | [![CI](https://github.com/cyphera-labs/cyphera-go/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-go/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-go/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-go/actions/workflows/codeql.yml) |
| Python | [![CI](https://github.com/cyphera-labs/cyphera-python/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-python/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-python/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-python/actions/workflows/codeql.yml) |
| Node | [![CI](https://github.com/cyphera-labs/cyphera-node/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-node/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-node/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-node/actions/workflows/codeql.yml) |
| .NET | [![CI](https://github.com/cyphera-labs/cyphera-dotnet/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-dotnet/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-dotnet/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-dotnet/actions/workflows/codeql.yml) |
| PHP | [![CI](https://github.com/cyphera-labs/cyphera-php/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-php/actions/workflows/ci.yml) | [![Security](https://github.com/cyphera-labs/cyphera-php/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-php/actions/workflows/codeql.yml) |
| Ruby | [![CI](https://github.com/cyphera-labs/cyphera-ruby/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-ruby/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-ruby/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-ruby/actions/workflows/codeql.yml) |
| Swift | [![CI](https://github.com/cyphera-labs/cyphera-swift/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-swift/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-swift/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-swift/actions/workflows/codeql.yml) |

### Integrations
| | CI | Security |
|---|---|---|
| Hibernate | [![CI](https://github.com/cyphera-labs/cyphera-hibernate/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-hibernate/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-hibernate/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-hibernate/actions/workflows/codeql.yml) |
| Kafka Connect | [![CI](https://github.com/cyphera-labs/cyphera-kafka-connect/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-kafka-connect/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-kafka-connect/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-kafka-connect/actions/workflows/codeql.yml) |
| Spring Boot | [![CI](https://github.com/cyphera-labs/cyphera-spring/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-spring/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-spring/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-spring/actions/workflows/codeql.yml) |
| Trino | [![CI](https://github.com/cyphera-labs/cyphera-trino/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-trino/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-trino/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-trino/actions/workflows/codeql.yml) |
| PostgreSQL | [![CI](https://github.com/cyphera-labs/cyphera-postgres/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-postgres/actions/workflows/ci.yml) | [![Security](https://github.com/cyphera-labs/cyphera-postgres/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-postgres/actions/workflows/codeql.yml) |
| BigQuery | [![CI](https://github.com/cyphera-labs/cyphera-bq/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-bq/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-bq/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-bq/actions/workflows/codeql.yml) |
| Snowflake | [![CI](https://github.com/cyphera-labs/cyphera-snowflake/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-snowflake/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-snowflake/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-snowflake/actions/workflows/codeql.yml) |
| Conformance | [![CI](https://github.com/cyphera-labs/cyphera-conformance/actions/workflows/conformance.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-conformance/actions/workflows/conformance.yml) | — |

### Keychains
| | CI | Security |
|---|---|---|
| Java | [![CI](https://github.com/cyphera-labs/keychain-java/actions/workflows/test.yml/badge.svg)](https://github.com/cyphera-labs/keychain-java/actions/workflows/test.yml) | [![CodeQL](https://github.com/cyphera-labs/keychain-java/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/keychain-java/actions/workflows/codeql.yml) |
| Rust | [![CI](https://github.com/cyphera-labs/keychain-rust/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/keychain-rust/actions/workflows/ci.yml) | [![Security](https://github.com/cyphera-labs/keychain-rust/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/keychain-rust/actions/workflows/codeql.yml) |
| Node | [![CI](https://github.com/cyphera-labs/keychain-node/actions/workflows/test.yml/badge.svg)](https://github.com/cyphera-labs/keychain-node/actions/workflows/test.yml) | [![CodeQL](https://github.com/cyphera-labs/keychain-node/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/keychain-node/actions/workflows/codeql.yml) |
| Python | [![CI](https://github.com/cyphera-labs/keychain-python/actions/workflows/test.yml/badge.svg)](https://github.com/cyphera-labs/keychain-python/actions/workflows/test.yml) | [![CodeQL](https://github.com/cyphera-labs/keychain-python/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/keychain-python/actions/workflows/codeql.yml) |
| .NET | [![CI](https://github.com/cyphera-labs/keychain-dotnet/actions/workflows/test.yml/badge.svg)](https://github.com/cyphera-labs/keychain-dotnet/actions/workflows/test.yml) | [![CodeQL](https://github.com/cyphera-labs/keychain-dotnet/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/keychain-dotnet/actions/workflows/codeql.yml) |
| Go | [![CI](https://github.com/cyphera-labs/keychain-go/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/keychain-go/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/keychain-go/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/keychain-go/actions/workflows/codeql.yml) |
| Swift | [![CI](https://github.com/cyphera-labs/keychain-swift/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/keychain-swift/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/keychain-swift/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/keychain-swift/actions/workflows/codeql.yml) |
| PHP | [![CI](https://github.com/cyphera-labs/keychain-php/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/keychain-php/actions/workflows/ci.yml) | [![Security](https://github.com/cyphera-labs/keychain-php/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/keychain-php/actions/workflows/codeql.yml) |
| Ruby | [![CI](https://github.com/cyphera-labs/keychain-ruby/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/keychain-ruby/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/keychain-ruby/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/keychain-ruby/actions/workflows/codeql.yml) |

## Cross-Language Compatible

All SDKs produce identical output for the same inputs:

```
Input:       123-45-6789
Java:        T01i6J-xF-07pX
Rust:        T01i6J-xF-07pX
Node:        T01i6J-xF-07pX
Python:      T01i6J-xF-07pX
Go:          T01i6J-xF-07pX
.NET:        T01i6J-xF-07pX
PHP:         T01i6J-xF-07pX
```

Encrypt in Go, decrypt in Python. One policy file, every language, every database.

## Quick Start

```python
from cyphera import Cyphera

c = Cyphera.load()
protected = c.protect("123-45-6789", "ssn")   # → "T01i6J-xF-07pX"
accessed = c.access(protected)                  # → "123-45-6789"
```

## Links

- **Website**: [cyphera.io](https://cyphera.io)
- **License**: Apache 2.0

---

Copyright 2026 Horizon Digital Engineering LLC
