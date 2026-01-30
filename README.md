## Linux Log Cleanup Automation

This project automates the cleanup of old log files on Linux systems to prevent disk space issues.

### How It Works
- Searches for log files older than 7 days
- Deletes outdated logs from `/var/log`
- Can be scheduled using cron

### Tools Used
- Bash
- Linux `find` command
- Cron

### Usage
```bash
chmod +x log_cleanup.sh
./log_cleanup.sh
