# Looking Glass Update Channel

Public update channel for Looking Glass.

The installed application checks `update.json` for the current stable version. Future updater revisions will use repository-hosted update payloads so updates do not depend on private source access or manually replacing the installation folder.

Current installed baseline: **1.3.3**.

## Update design

- Source remains private in `IllBEAKER5164/Looking-Glass`.
- Public update metadata and distributable payloads live here.
- `CHECK UPDATE` is the user-facing update entry point.
- Updates are expected to verify SHA-256 before replacement and restart Looking Glass after a successful update.
