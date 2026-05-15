# Kontracts-grpc

![CI](https://github.com/komrad-company/Kontracts/actions/workflows/ci.yml/badge.svg) ![License: AGPL-3.0](https://img.shields.io/badge/license-AGPL--3.0-blue) ![Rust 2024](https://img.shields.io/badge/rust-edition%202024-orange?logo=rust)

gRPC contract definitions for Komrad — generated Rust types for all services.

## Services

- `kolektor.v1.KolektorConfigService` — Parser management (AddParser, RemoveParser, GetMetrics, GetStatus)

## Usage

```toml
kontracts-grpc = { git = "https://github.com/komrad-company/Kontracts-grpc.git" }
```

## License

AGPL-3.0-or-later
