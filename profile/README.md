# Cyphera

**Open-source cryptography infrastructure.**

Data obfuscation, key management, PKI, and secrets tooling. Self-hosted, cross-language, no vendor lock-in.

---

## Data Obfuscation

Format-preserving encryption (NIST SP 800-38G FF1/FF3), AES-GCM, data masking, and hashing. One API across nine languages.

### SDKs

| Language | Package | Install | CI | Security |
|----------|---------|---------|----|----|
| [Java](https://github.com/cyphera-labs/cyphera-java) | [![Maven Central](https://img.shields.io/maven-central/v/io.cyphera/cyphera)](https://central.sonatype.com/artifact/io.cyphera/cyphera) | `io.cyphera:cyphera` | [![CI](https://github.com/cyphera-labs/cyphera-java/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-java/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-java/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-java/actions/workflows/codeql.yml) |
| [Rust](https://github.com/cyphera-labs/cyphera-rust) | [![crates.io](https://img.shields.io/crates/v/cyphera)](https://crates.io/crates/cyphera) | `cyphera` | [![CI](https://github.com/cyphera-labs/cyphera-rust/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-rust/actions/workflows/ci.yml) | [![Security](https://github.com/cyphera-labs/cyphera-rust/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-rust/actions/workflows/codeql.yml) |
| [Go](https://github.com/cyphera-labs/cyphera-go) | [![Go](https://img.shields.io/badge/go-pkg-blue)](https://pkg.go.dev/github.com/cyphera-labs/cyphera-go) | `go get github.com/cyphera-labs/cyphera-go` | [![CI](https://github.com/cyphera-labs/cyphera-go/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-go/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-go/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-go/actions/workflows/codeql.yml) |
| [Python](https://github.com/cyphera-labs/cyphera-python) | [![PyPI](https://img.shields.io/pypi/v/cyphera)](https://pypi.org/project/cyphera/) | `pip install cyphera` | [![CI](https://github.com/cyphera-labs/cyphera-python/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-python/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-python/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-python/actions/workflows/codeql.yml) |
| [Node.js](https://github.com/cyphera-labs/cyphera-node) | [![npm](https://img.shields.io/npm/v/cyphera)](https://www.npmjs.com/package/cyphera) | `npm install cyphera` | [![CI](https://github.com/cyphera-labs/cyphera-node/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-node/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-node/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-node/actions/workflows/codeql.yml) |
| [.NET](https://github.com/cyphera-labs/cyphera-dotnet) | [![NuGet](https://img.shields.io/nuget/v/Cyphera)](https://www.nuget.org/packages/Cyphera) | `dotnet add package Cyphera` | [![CI](https://github.com/cyphera-labs/cyphera-dotnet/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-dotnet/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-dotnet/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-dotnet/actions/workflows/codeql.yml) |
| [PHP](https://github.com/cyphera-labs/cyphera-php) | [![Packagist](https://img.shields.io/packagist/v/cyphera/cyphera)](https://packagist.org/packages/cyphera/cyphera) | `composer require cyphera/cyphera` | [![CI](https://github.com/cyphera-labs/cyphera-php/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-php/actions/workflows/ci.yml) | [![Security](https://github.com/cyphera-labs/cyphera-php/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-php/actions/workflows/codeql.yml) |
| [Ruby](https://github.com/cyphera-labs/cyphera-ruby) | [![Gem](https://img.shields.io/gem/v/cyphera)](https://rubygems.org/gems/cyphera) | `gem install cyphera` | [![CI](https://github.com/cyphera-labs/cyphera-ruby/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-ruby/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-ruby/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-ruby/actions/workflows/codeql.yml) |
| [Swift](https://github.com/cyphera-labs/cyphera-swift) | [![SPI](https://img.shields.io/endpoint?url=https%3A%2F%2Fswiftpackageindex.com%2Fapi%2Fpackages%2Fcyphera-labs%2Fcyphera-swift%2Fbadge%3Ftype%3Dswift-versions)](https://swiftpackageindex.com/cyphera-labs/cyphera-swift) | `.package(url: "...cyphera-swift.git")` | [![CI](https://github.com/cyphera-labs/cyphera-swift/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-swift/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-swift/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-swift/actions/workflows/codeql.yml) |

### Keychains

Key resolution across providers: File, Env, AWS KMS, GCP KMS, Azure Key Vault, HashiCorp Vault.

| Language | CI | Security |
|----------|----|----------|
| [Java](https://github.com/cyphera-labs/keychain-java) | [![CI](https://github.com/cyphera-labs/keychain-java/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/keychain-java/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/keychain-java/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/keychain-java/actions/workflows/codeql.yml) |
| [Go](https://github.com/cyphera-labs/keychain-go) | [![CI](https://github.com/cyphera-labs/keychain-go/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/keychain-go/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/keychain-go/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/keychain-go/actions/workflows/codeql.yml) |
| [Python](https://github.com/cyphera-labs/keychain-python) | [![CI](https://github.com/cyphera-labs/keychain-python/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/keychain-python/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/keychain-python/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/keychain-python/actions/workflows/codeql.yml) |
| [Rust](https://github.com/cyphera-labs/keychain-rust) | [![CI](https://github.com/cyphera-labs/keychain-rust/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/keychain-rust/actions/workflows/ci.yml) | [![Security](https://github.com/cyphera-labs/keychain-rust/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/keychain-rust/actions/workflows/codeql.yml) |
| [Node.js](https://github.com/cyphera-labs/keychain-node) | [![CI](https://github.com/cyphera-labs/keychain-node/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/keychain-node/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/keychain-node/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/keychain-node/actions/workflows/codeql.yml) |
| [.NET](https://github.com/cyphera-labs/keychain-dotnet) | [![CI](https://github.com/cyphera-labs/keychain-dotnet/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/keychain-dotnet/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/keychain-dotnet/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/keychain-dotnet/actions/workflows/codeql.yml) |
| [PHP](https://github.com/cyphera-labs/keychain-php) | [![CI](https://github.com/cyphera-labs/keychain-php/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/keychain-php/actions/workflows/ci.yml) | [![Security](https://github.com/cyphera-labs/keychain-php/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/keychain-php/actions/workflows/codeql.yml) |
| [Ruby](https://github.com/cyphera-labs/keychain-ruby) | [![CI](https://github.com/cyphera-labs/keychain-ruby/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/keychain-ruby/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/keychain-ruby/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/keychain-ruby/actions/workflows/codeql.yml) |
| [Swift](https://github.com/cyphera-labs/keychain-swift) | [![CI](https://github.com/cyphera-labs/keychain-swift/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/keychain-swift/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/keychain-swift/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/keychain-swift/actions/workflows/codeql.yml) |

### Platform Integrations

| Platform | Type | Powered By | SDK Version | CI | Security |
|----------|------|------------|-------------|----|----------|
| [Trino](https://github.com/cyphera-labs/cyphera-trino) | SQL UDF plugin | cyphera-java | 0.0.1-alpha.3 | [![CI](https://github.com/cyphera-labs/cyphera-trino/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-trino/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-trino/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-trino/actions/workflows/codeql.yml) |
| [PostgreSQL](https://github.com/cyphera-labs/cyphera-postgres) | Native extension (pgrx) | cyphera-rust | 0.0.1-alpha.1 | [![CI](https://github.com/cyphera-labs/cyphera-postgres/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-postgres/actions/workflows/ci.yml) | [![Security](https://github.com/cyphera-labs/cyphera-postgres/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-postgres/actions/workflows/codeql.yml) |
| [Snowflake](https://github.com/cyphera-labs/cyphera-snowflake) | Java UDF | cyphera-java | 0.0.1-alpha.3 | [![CI](https://github.com/cyphera-labs/cyphera-snowflake/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-snowflake/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-snowflake/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-snowflake/actions/workflows/codeql.yml) |
| [Databricks](https://github.com/cyphera-labs/cyphera-databricks) | Spark UDF | cyphera-java | 0.0.1-alpha.3 | [![CI](https://github.com/cyphera-labs/cyphera-databricks/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-databricks/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-databricks/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-databricks/actions/workflows/codeql.yml) |
| [BigQuery](https://github.com/cyphera-labs/cyphera-bq) | Remote UDF | cyphera-go | not wired | [![CI](https://github.com/cyphera-labs/cyphera-bq/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-bq/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-bq/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-bq/actions/workflows/codeql.yml) |
| [Informatica](https://github.com/cyphera-labs/cyphera-informatica) | Java transformation | cyphera-java | 0.0.1-alpha.3 | [![CI](https://github.com/cyphera-labs/cyphera-informatica/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-informatica/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-informatica/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-informatica/actions/workflows/codeql.yml) |
| [Striim](https://github.com/cyphera-labs/cyphera-striim) | UDF + Open Processor | cyphera-java | 0.0.1-alpha.3 | [![CI](https://github.com/cyphera-labs/cyphera-striim/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-striim/actions/workflows/ci.yml) | [![Security](https://github.com/cyphera-labs/cyphera-striim/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-striim/actions/workflows/codeql.yml) |
| [Kafka Connect](https://github.com/cyphera-labs/cyphera-kafka-connect) | SMT (Single Message Transform) | cyphera-java | 0.0.1-alpha.3 | [![CI](https://github.com/cyphera-labs/cyphera-kafka-connect/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-kafka-connect/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-kafka-connect/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-kafka-connect/actions/workflows/codeql.yml) |
| [Hibernate](https://github.com/cyphera-labs/cyphera-hibernate) | @CypheraProtect annotation | cyphera-java | 0.0.1-alpha.3 | [![CI](https://github.com/cyphera-labs/cyphera-hibernate/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-hibernate/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-hibernate/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-hibernate/actions/workflows/codeql.yml) |
| [Apache NiFi](https://github.com/cyphera-labs/cyphera-nifi) | NiFi Processor | cyphera-java | 0.0.1-alpha.3 | [![CI](https://github.com/cyphera-labs/cyphera-nifi/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-nifi/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-nifi/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-nifi/actions/workflows/codeql.yml) |
| [Apache Flink](https://github.com/cyphera-labs/cyphera-flink) | Flink SQL UDF | cyphera-java | 0.0.1-alpha.3 | [![CI](https://github.com/cyphera-labs/cyphera-flink/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-flink/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-flink/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-flink/actions/workflows/codeql.yml) |
| [StreamSets](https://github.com/cyphera-labs/cyphera-streamsets) | StreamSets Processor | cyphera-java | 0.0.1-alpha.3 | [![CI](https://github.com/cyphera-labs/cyphera-streamsets/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-streamsets/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-streamsets/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-streamsets/actions/workflows/codeql.yml) |
| [Spring Boot](https://github.com/cyphera-labs/cyphera-spring) | Auto-configured starter | cyphera-java | 0.0.1-alpha.3 | [![CI](https://github.com/cyphera-labs/cyphera-spring/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-spring/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/cyphera-spring/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-spring/actions/workflows/codeql.yml) |
| [Conformance](https://github.com/cyphera-labs/cyphera-conformance) | Cross-language test suite | — | — | [![CI](https://github.com/cyphera-labs/cyphera-conformance/actions/workflows/conformance.yml/badge.svg)](https://github.com/cyphera-labs/cyphera-conformance/actions/workflows/conformance.yml) | — |

---

## Key Management

KMIP 1.4 key management — open-source server and client libraries for nine languages.

### Server

| | |
|---|---|
| [**Open KMIP Server**](https://github.com/cyphera-labs/open-kmip-server) | 27 KMIP operations, mTLS, REST API, server-side crypto, audit, dashboard — `v0.1.0-alpha.1` |

### KMIP Client Libraries

27 KMIP 1.4 operations per library. Works with Cyphera Open KMIP Server or any KMIP-compliant system.

| Language | CI | Security |
|----------|----|----------|
| [Go](https://github.com/cyphera-labs/kmip-go) | [![CI](https://github.com/cyphera-labs/kmip-go/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/kmip-go/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/kmip-go/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/kmip-go/actions/workflows/codeql.yml) |
| [Java](https://github.com/cyphera-labs/kmip-java) | [![CI](https://github.com/cyphera-labs/kmip-java/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/kmip-java/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/kmip-java/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/kmip-java/actions/workflows/codeql.yml) |
| [Python](https://github.com/cyphera-labs/kmip-python) | [![CI](https://github.com/cyphera-labs/kmip-python/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/kmip-python/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/kmip-python/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/kmip-python/actions/workflows/codeql.yml) |
| [Node.js](https://github.com/cyphera-labs/kmip-node) | [![CI](https://github.com/cyphera-labs/kmip-node/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/kmip-node/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/kmip-node/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/kmip-node/actions/workflows/codeql.yml) |
| [Rust](https://github.com/cyphera-labs/kmip-rust) | [![CI](https://github.com/cyphera-labs/kmip-rust/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/kmip-rust/actions/workflows/ci.yml) | [![Security](https://github.com/cyphera-labs/kmip-rust/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/kmip-rust/actions/workflows/codeql.yml) |
| [.NET](https://github.com/cyphera-labs/kmip-dotnet) | [![CI](https://github.com/cyphera-labs/kmip-dotnet/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/kmip-dotnet/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/kmip-dotnet/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/kmip-dotnet/actions/workflows/codeql.yml) |
| [PHP](https://github.com/cyphera-labs/kmip-php) | [![CI](https://github.com/cyphera-labs/kmip-php/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/kmip-php/actions/workflows/ci.yml) | [![Security](https://github.com/cyphera-labs/kmip-php/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/kmip-php/actions/workflows/codeql.yml) |
| [Ruby](https://github.com/cyphera-labs/kmip-ruby) | [![CI](https://github.com/cyphera-labs/kmip-ruby/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/kmip-ruby/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/kmip-ruby/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/kmip-ruby/actions/workflows/codeql.yml) |
| [Swift](https://github.com/cyphera-labs/kmip-swift) | [![CI](https://github.com/cyphera-labs/kmip-swift/actions/workflows/ci.yml/badge.svg)](https://github.com/cyphera-labs/kmip-swift/actions/workflows/ci.yml) | [![CodeQL](https://github.com/cyphera-labs/kmip-swift/actions/workflows/codeql.yml/badge.svg)](https://github.com/cyphera-labs/kmip-swift/actions/workflows/codeql.yml) |

---

## PKI & Certificates

Certificate authority and PKI lifecycle server.

| | |
|---|---|
| [**Open PKI Server**](https://github.com/cyphera-labs/open-pki-server) | CA hierarchy, issuance, CRL, OCSP, CSR support, dashboard — `v0.1.0-alpha.1` |

---

**Website**: [cyphera.io](https://cyphera.io) · **License**: Apache 2.0

Cyphera is a [Horizon Digital Engineering LLC](https://horizondigital.dev) project.
