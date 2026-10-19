# Backup Script Guide

## 1. Purpose

The `backup.sh` script automates the backup of the `app-data` directory. It creates a `backups` directory if needed and compresses the source directory into a `.tar.gz` archive. Each archive includes a timestamp in its filename to help distinguish backups created at different times.

## 2. Full Bash Script

```bash
#!/bin/bash
# Automated Backup Script for CloudNova Technologies

SOURCE_DIR="app-data"
BACKUP_DIR="backups"
TIMESTAMP=$(date +"%Y%m%d_%H%M%S")

echo "Initiating automated backup..."

# Create the backup directory if it does not exist
mkdir -p "$BACKUP_DIR"

# Compress the source directory into a tarball (.tar.gz)
tar -czf "$BACKUP_DIR/backup_$TIMESTAMP.tar.gz" "$SOURCE_DIR"

echo "Backup completed successfully at $TIMESTAMP!"
```

## 3. File Permissions

The command `chmod +x backup.sh` adds executable permission to the script. This allows it to be run using `./backup.sh` instead of opening it as a text file. Without executable permission, running the script directly may produce a `Permission denied` error.

## 4. Cron Schedule

The Cron expression used is:

```cron
0 2 * * * /root/backup.sh
```

The five time fields are:

| Field | Value | Explanation |
|---|---|---|
| Minute | `0` | At minute zero |
| Hour | `2` | At 2 AM |
| Day of Month | `*` | Every day of the month |
| Month | `*` | Every month |
| Day of Week | `*` | Every day of the week |

This schedule runs `/root/backup.sh` every day at 2:00 AM, using the system's configured local time.
