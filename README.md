# 🛠️ FirmX-Ray - Advanced Firmware Vulnerability Scanner

**FirmX-Ray** is a powerful Python-based command-line tool for automated firmware vulnerability analysis and scanning. Designed for cybersecurity professionals, penetration testers, and reverse engineers, it efficiently extracts and analyzes firmware images for potential security flaws and configurations.

---

## 👨‍💻 Developed By
**Jivitesh Khatri**

---

## 🚀 Features

- 🔍 Firmware extraction using `binwalk`
- 📁 File system scanning
- 🧠 Binary analysis with optional CVE lookup
- 🔐 Weak cryptographic key detection
- 🌐 Network service parser (init/network config analysis)
- ⚡ Fast multithreaded analysis
- 🧾 Enhanced search for:
  - SSL files (`.pem`, `.crt`, `/etc/ssl/`)
  - Config files (`.conf`, `.cfg`, `.config`)
  - Script files (`.sh`, `.py`, etc.)
  - Binary files (`.bin`)
  - URLs, IP addresses, Email addresses
  - Common web server strings (e.g., `nginx`, `httpd`)
  - Common binaries (`ssh`, `tftp`, `dropbear`)
- 📊 JSON or HTML report generation

---

## 📦 Installation

### Prerequisites

Install system dependencies:

```bash
sudo apt update
sudo apt install binwalk python3 python3-pip
python3 -m venv venv
source venv/bin/activate
