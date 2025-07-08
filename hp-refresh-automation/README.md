# HP Refresh Automation

This repository contains tools and scripts for automating the refresh of legacy HP Desktop Minis. Designed for IT technicians tasked with large-scale hardware swaps, it streamlines imaging, pre-checks, and post-deployment validation.

## 🔧 Features

- 🔍 Inventory collection (device specs, user info, asset tags)
- 🧹 Cleanup old software and prep systems for return
- ⚙️ Post-refresh configuration (rename PC, rejoin domain, etc.)
- 📄 Includes templates for asset tracking and service documentation

## 📂 Directory Overview

- `scripts/` – PowerShell scripts used during different stages of refresh
- `logs/` – Output logs for audits and troubleshooting
- `templates/` – CSV and documentation templates
- `images/` – Optional diagrams or screenshots

## 🚀 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/hp-refresh-automation.git
   ```
2. Open PowerShell as admin.
3. Run the desired script in the `scripts/` folder based on your stage of the process.

## 📌 Notes

- Built and tested in a real enterprise refresh at UC Davis Health.
- Scripts assume access to an imaging solution and ServiceNow or other ticketing system integration.

## 📜 License

MIT License
