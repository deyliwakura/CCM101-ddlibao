# Laboratory 09 – The Cloud Automation Engineer

## Mission Overview

This mission focuses on automating routine cloud administration tasks using Bash scripts and the Linux Cron scheduler. A backup script is created to compress sample application data into a timestamped archive, reducing the need for manual backups.

## Objectives

- Understand Bash scripts, variables, and Cron jobs.
- Create sample application data and a backup script.
- Modify script permissions using `chmod +x`.
- Execute the script and verify the generated backup archive.
- Schedule the backup to run every day at 2:00 AM.
- Document the script and Cron configuration in Markdown.

## Commands Executed

```bash
mkdir -p app-data
echo "This is critical client data." > app-data/data.txt
nano backup.sh
./backup.sh
chmod +x backup.sh
./backup.sh
ls -l backups/
tar -tzf backups/*.tar.gz
crontab -l
env EDITOR=nano crontab -e
```

## Skills Learned

I learned how to write a Bash script, use variables, compress files with `tar`, and change file permissions with `chmod`. I also learned how Cron schedules tasks automatically. This mission improved my command-line skills and showed how automation can reduce repetitive work and human error. I also learned that scripts and schedules must be tested carefully to avoid repeating mistakes automatically.
