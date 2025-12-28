## System Architecture Plan

The workflow is designed so that:
- All DevOps projects live in GitHub
- Ubuntu and Arch act as independent environments
- No shared partitions are required
- Git acts as CI/CD between OSes

This allows switching OSes without losing work.
