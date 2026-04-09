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
| [Hibernate/JPA](https://github.com/cyphera-labs/cyphera-hibernate-jpa) | cyphera-hibernate-jpa | AttributeConverter | cyphera-java | 0.0.1-alpha.3 |
| [Spring Boot](https://github.com/cyphera-labs/cyphera-spring) | cyphera-spring | Auto-configured starter | cyphera-java | 0.0.1-alpha.3 |

## Cross-Language Compatible

All seven SDKs produce identical output for the same inputs:

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
