# Changelog

All notable changes to this project are documented here.

## Unreleased

- Persist denied authorization and expired/revoked secret access before rejecting operations.
- Validate rotation expiry before mutating secret values or versions.
- Library migration: `list()` and `auditLog()` now return promises and must be awaited. CLI syntax and output remain unchanged.

## [1.0.0] - 2026-10-07

- Added AES-256-GCM encrypted local secret storage.
- Added scoped bearer tokens, secret rotation, expiry, and revocation.
- Added atomic persistence, tamper detection, and plaintext-safe audit events.
- Added automated tests, continuous integration, dependency monitoring, and security guidance.
