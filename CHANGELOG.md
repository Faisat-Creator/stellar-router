# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.0] - 2026-03-14

### Added
- `router-core`: central dispatcher with route registration and pause controls
- `router-registry`: versioned contract address registry with deprecation support
- `router-access`: role-based ACL with blacklisting and role admins
- `router-middleware`: rate limiting, call logging, and route enable/disable
- `router-timelock`: delayed execution queue for sensitive administrative changes
- `router-multicall`: batch cross-contract calls in a single transaction
- 45 tests across all contracts

[Unreleased]: https://github.com/Maki-Zeninn/stellar-router/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/Maki-Zeninn/stellar-router/releases/tag/v0.1.0
