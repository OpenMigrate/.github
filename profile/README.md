# OpenMigrate

## Description
OpenMigrate is a cloud-agnostic server migration tool designed to replicate entire server systems from any source to any cloud. It operates in two main parts:
- **Agent**: Runs on the source server, scans and collects system metadata, and replicates data.
- **Replicator**: Receives metadata and replicated data, storing it for recovery or cutover.

## Features
- Lightweight agent for system discovery and replication.
- Modular replicator service for processing and storage.
- Basic RBAC and authentication.
- Planned support for SSO (Azure AD, etc.).
- Future block-level change tracking and incremental replication.

## License
Apache License 2.0
