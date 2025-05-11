# 📁 SFTP Versioned File System

A secure, version-controlled file system built over SFTP, allowing users to upload, retrieve, and manage historical versions of files in remote storage environments. Powered by `libssh`, Python, and lightweight metadata tracking.

## 🔒 What It Does

- 🔐 Secure file transfer over SFTP using SSH
- 📜 Version tracking for each uploaded file
- 🗃️ Restore previous versions on demand
- 🛡️ Optional encryption layer for stored data (planned)

## 💡 Why?

Traditional SFTP servers overwrite files with no history. This system preserves **file integrity** and **history**, making it useful for:

- Developers needing remote version backup
- Teams working over SSH-accessible infrastructure
- Lightweight remote archival

## ⚙️ Tech Stack

- **Python 3.x**
- **libssh** (via C or Python bindings)
- **SQLite** (for version metadata)
- Optional: **Flask** for a local web dashboard

## 🚀 Getting Started

### Prerequisites

- `Python 3.10+`
- `libssh` installed on your system
- Access to an SSH/SFTP server
- `pip install -r requirements.txt`

### Clone the Repo

```bash
git clone https://github.com/yourusername/sftp-versioned-fs.git
cd sftp-versioned-fs
