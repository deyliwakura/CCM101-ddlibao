# Automation Research

## 1. Bash Script

A Bash script is a text file containing commands that the Bash shell executes in sequence. It helps automate repeated tasks instead of requiring a user to type each command manually. The `#!/bin/bash` line, called the shebang, tells the system to use Bash to interpret the script.

## 2. Variables

Variables store values, such as directory paths, filenames, or timestamps, so they can be reused in a script. For example, `$BACKUP_DIR` stores the location where backup files will be saved. Using variables makes scripts easier to maintain because a value can be changed in one place instead of editing several commands.

## 3. Cron Job

A cron job is a scheduled task managed by the Linux Cron service. It runs a command or script at specified times without requiring someone to start it manually. Cron jobs are useful in cloud operations because they can automate routine tasks such as backups, maintenance, and log processing.
