---
name: automated-backup-recovery
description: Design and manage automated data backup and disaster recovery plans.
---

# Automated Backup & Recovery

This skill ensures that your data is safe and can be restored quickly in case of a system failure.

## Instructions

1. Set up cron jobs for automated database dumps (Postgres, Mongo).
2. Store backups in geo-redundant cloud storage (e.g., S3 Glacier).
3. Implement 'Point-in-Time Recovery' (PITR) for critical databases.
4. Regularly test the restoration process to ensure backups work.
5. Encrypt backup files at rest and in transit.

## Examples

- "Set up a daily automated backup for my production database."
- "Explain how to recover my site if the main server goes down."