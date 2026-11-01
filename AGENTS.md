# jinsei-managed-ci
Read-only GitHub Action for validating repository profiles; GitHub: `rasokiwayami/jinsei-managed-ci`.
status: dormant

Work only when explicitly asked.

## Repository boundaries
- Keep the GitHub Action read-only and sanitized; do not add repository creation, visibility changes, release/deploy, secret mutation, scheduling or control-plane behavior.
- Do not log profile contents or private runtime data; preserve pinned dependency and Action references.
