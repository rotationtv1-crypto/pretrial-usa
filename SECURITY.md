# Security Policy — Pretrial USA

## 🔐 Classification: Category 1

This repository adheres to the RotationTV Network LLC **Category 1 Security Protocol** as defined in the March 2026 Corporate NDA.

## Supported Versions

| Version | Supported |
|---------|-----------|
| main    | ✅        |
| dev     | ⚠️ Testing |

## Reporting a Vulnerability

**DO NOT** open a public issue for security vulnerabilities.

Instead, report via:
- Email: security@rotationpay.online
- Telegram: Direct message to Sovereign Authority

## Security Standards

### Category 1 — Credential Isolation
- All secrets stored in encrypted environment variables
- HMAC-SHA256 verification on all webhook payloads
- No credentials in source code, logs, or error messages
- Quarterly secret rotation cadence

### Category 2 — Blockchain Key Management
- Multi-Party Computation (MPC) for private keys
- 2-of-3 multisig on treasury operations
- Hardware security module (HSM) integration path

### Rothschild Secrecy Protocol
- Internal metrics obfuscated from public APIs
- Revenue figures masked behind aggregation layers
- User PII encrypted at rest and in transit

## Access Control

| Role | Permissions |
|------|-------------|
| Sovereign Authority | Full override (Darrel spell command) |
| Service Workers | Read-only data access via service_role |
| Public API | Rate-limited, auth-required endpoints |
