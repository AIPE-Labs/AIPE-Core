# Changelog

## 0.1.0 — 2026-11-27

First tagged release.

- Define offline JSON Schema 2020-12 Engineering State and domain boundaries.
- Specify SI quantities, evidence, provenance, attribution and semantic contracts.
- Add a synthetic 10 kW DAB requirement example without physical performance claims.
- Add reference/status validation, negative tests and open-source CI.
- Record the ecosystem architecture freeze and audit.
- Move the repository to the `AIPE-Labs` organisation. Schema `$id` and `$ref`
  values now use `https://raw.githubusercontent.com/AIPE-Labs/AIPE-Core/v0.1.0/schemas/`,
  which this release tag makes resolvable. The earlier
  `FulongLi/AIPE-Core` identifiers were never published under a tag;
  repositories that vendored them should refresh their copy from this release.
