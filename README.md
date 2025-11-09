# Bash System Maintenance Suite

A comprehensive Bash-based system maintenance toolkit that automates key system administration tasks on Linux systems.  
This project is designed for server administrators, students, and developers who want a reliable command-line interface 
to manage backups, system updates, log monitoring, and system health diagnostics.

---

## 🚀 Features

| Feature | Description | Benefit |
|--------|-------------|---------|
| **Backup Automation** | Creates time-stamped compressed backups with auto-cleanup | Ensures data safety and storage efficiency |
| **System Update & Cleanup** | Performs package updates and old file cleanup | Keeps the system secure & optimized |
| **Log Monitoring** | Tracks and alerts for warnings/errors in system logs | Helps detect system issues early |
| **System Health Check (Extended)** | Monitors CPU, RAM, disk & running services | Prevents performance bottlenecks |
| **User Account Management (Extended)** | Allows add/lock/remove user accounts | Improves multi-user system security |
| **Remote Backup Sync (Extended)** | Syncs backups to remote servers via `rsync` | Provides disaster recovery support |

---

## 📁 Project Structure

```
System-Maintenance-Suite/
│── backup.sh
│── update_cleanup.sh
│── log_monitor.sh
│── menu.sh
│── health.sh               # (Extended Feature)
│── useradmin.sh            # (Extended Feature)
│── rsync_backup.sh         # (Extended Feature)
│── exclude.txt
│── config.env
│── logs/
│── backups/
│── Project_Report.docx
│── screenshots/
```

---
