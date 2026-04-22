# Cyphera

**Open-source cryptography infrastructure.**

Data obfuscation, key management, PKI, and secrets tooling. Self-hosted, cross-language, no vendor lock-in.

---

## Infrastructure

| Server | What it does | Status |
|--------|-------------|--------|
| [**Open KMIP Server**](https://github.com/cyphera-labs/open-kmip-server) | KMIP 1.4 key management — 27 operations, mTLS, REST API, server-side crypto, audit, dashboard | `v0.1.0-alpha.1` |
| [**Open PKI Server**](https://github.com/cyphera-labs/open-pki-server) | Certificate authority — CA hierarchy, issuance, CRL, OCSP, CSR support, dashboard | `v0.1.0-alpha.1` |

## Data Obfuscation SDKs

Format-preserving encryption (NIST SP 800-38G FF1/FF3), AES-GCM, data masking, and hashing. One API across nine languages.

| Language | Repo | Install |
|----------|------|---------|
| Java | [cyphera-java](https://github.com/cyphera-labs/cyphera-java) | `io.cyphera:cyphera` |
| Go | [cyphera-go](https://github.com/cyphera-labs/cyphera-go) | `go get github.com/cyphera-labs/cyphera-go` |
| Python | [cyphera-python](https://github.com/cyphera-labs/cyphera-python) | `pip install cyphera` |
| Rust | [cyphera-rust](https://github.com/cyphera-labs/cyphera-rust) | `cargo add cyphera` |
| Node.js | [cyphera-node](https://github.com/cyphera-labs/cyphera-node) | `npm install cyphera` |
| .NET | [cyphera-dotnet](https://github.com/cyphera-labs/cyphera-dotnet) | `dotnet add package Cyphera` |
| PHP | [cyphera-php](https://github.com/cyphera-labs/cyphera-php) | `composer require cyphera/cyphera` |
| Ruby | [cyphera-ruby](https://github.com/cyphera-labs/cyphera-ruby) | `gem install cyphera` |
| Swift | [cyphera-swift](https://github.com/cyphera-labs/cyphera-swift) | `.package(url: "...cyphera-swift.git")` |

## KMIP Client Libraries

27 KMIP 1.4 operations per library. Works with Cyphera Open KMIP Server or any KMIP-compliant system.

| Language | Repo |
|----------|------|
| Go | [kmip-go](https://github.com/cyphera-labs/kmip-go) |
| Java | [kmip-java](https://github.com/cyphera-labs/kmip-java) |
| Python | [kmip-python](https://github.com/cyphera-labs/kmip-python) |
| Node.js | [kmip-node](https://github.com/cyphera-labs/kmip-node) |
| Rust | [kmip-rust](https://github.com/cyphera-labs/kmip-rust) |
| .NET | [kmip-dotnet](https://github.com/cyphera-labs/kmip-dotnet) |
| PHP | [kmip-php](https://github.com/cyphera-labs/kmip-php) |
| Ruby | [kmip-ruby](https://github.com/cyphera-labs/kmip-ruby) |
| Swift | [kmip-swift](https://github.com/cyphera-labs/kmip-swift) |

## Platform Integrations

| Platform | Repo | Type |
|----------|------|------|
| Hibernate | [cyphera-hibernate](https://github.com/cyphera-labs/cyphera-hibernate) | JPA annotation |
| Kafka Connect | [cyphera-kafka-connect](https://github.com/cyphera-labs/cyphera-kafka-connect) | SMT |
| Spring Boot | [cyphera-spring](https://github.com/cyphera-labs/cyphera-spring) | Auto-configured starter |
| Trino | [cyphera-trino](https://github.com/cyphera-labs/cyphera-trino) | SQL UDF plugin |
| PostgreSQL | [cyphera-postgres](https://github.com/cyphera-labs/cyphera-postgres) | Native extension (pgrx) |
| Snowflake | [cyphera-snowflake](https://github.com/cyphera-labs/cyphera-snowflake) | Java UDF |
| Databricks | [cyphera-databricks](https://github.com/cyphera-labs/cyphera-databricks) | Spark UDF |
| BigQuery | [cyphera-bq](https://github.com/cyphera-labs/cyphera-bq) | Remote UDF |
| Informatica | [cyphera-informatica](https://github.com/cyphera-labs/cyphera-informatica) | Java transformation |
| Striim | [cyphera-striim](https://github.com/cyphera-labs/cyphera-striim) | UDF + Open Processor |
| Apache NiFi | [cyphera-nifi](https://github.com/cyphera-labs/cyphera-nifi) | NiFi Processor |
| Apache Flink | [cyphera-flink](https://github.com/cyphera-labs/cyphera-flink) | Flink SQL UDF |
| StreamSets | [cyphera-streamsets](https://github.com/cyphera-labs/cyphera-streamsets) | StreamSets Processor |

## Keychain Libraries

Key resolution across providers: File, Env, AWS KMS, GCP KMS, Azure Key Vault, HashiCorp Vault.

| Language | Repo |
|----------|------|
| Java | [keychain-java](https://github.com/cyphera-labs/keychain-java) |
| Go | [keychain-go](https://github.com/cyphera-labs/keychain-go) |
| Python | [keychain-python](https://github.com/cyphera-labs/keychain-python) |
| Rust | [keychain-rust](https://github.com/cyphera-labs/keychain-rust) |
| Node.js | [keychain-node](https://github.com/cyphera-labs/keychain-node) |
| .NET | [keychain-dotnet](https://github.com/cyphera-labs/keychain-dotnet) |
| PHP | [keychain-php](https://github.com/cyphera-labs/keychain-php) |
| Ruby | [keychain-ruby](https://github.com/cyphera-labs/keychain-ruby) |
| Swift | [keychain-swift](https://github.com/cyphera-labs/keychain-swift) |

## Cross-Language Compatible

All data obfuscation SDKs produce identical output for the same inputs:

```
Input:       123-45-6789
Java:        T01i6J-xF-07pX
Rust:        T01i6J-xF-07pX
Go:          T01i6J-xF-07pX
Python:      T01i6J-xF-07pX
Node:        T01i6J-xF-07pX
.NET:        T01i6J-xF-07pX
PHP:         T01i6J-xF-07pX
```

Encrypt in Go, decrypt in Python. Same configuration, every language, every platform.

---

**Website**: [cyphera.io](https://cyphera.io) · **License**: Apache 2.0

Cyphera is a [Horizon Digital Engineering LLC](https://horizondigital.dev) project.
