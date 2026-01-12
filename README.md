# File System Backup Tool

A lightweight, reliable, and fully local automatic backup tool for Windows.

File System Backup Tool is designed for real-world Windows usage scenarios where stability, safety, and transparency matter more than flashy features.  
It runs entirely on your local machine — **no cloud, no network, no data collection**.

---

## Key Features

- **Scheduled Backups**
  - Daily / Weekly / Monthly schedules
  - Minute-level time precision
  - Multiple backup tasks supported

- **Safe Path Validation**
  - Prevents source and destination path conflicts
  - Blocks infinite recursive backups
  - Validates all tasks before execution

- **Background & Silent Operation**
  - System tray support
  - Silent startup and auto-start on boot
  - Runs quietly without interrupting your work

- **Advanced Backup Mode (Administrator)**
  - Uses Windows Robocopy `/B` mode
  - Can copy locked and in-use files
  - Multi-threaded copy with retry mechanism
  - Automatically falls back to standard mode if not elevated

- **Clear & Auditable Logs**
  - Per-task Markdown backup logs
  - Daily summary log files
  - Records source, destination, method, duration, and result

- **Smart Exclusions**
  - Automatically skips common build, cache, and VCS folders
  - Avoids copying previous backup directories
  - Optimized for development and workstation environments

---

## Philosophy

- Fully **offline**
- Fully **local**
- Fully **free**
- No background services
- No hidden behavior

This tool is built to behave like a system utility — predictable, quiet, and dependable.

---

## Best For

- Developers and engineers
- Workstations and long-running PCs
- Users who prefer local backups over cloud solutions
- Anyone who values reliability over feature bloat
