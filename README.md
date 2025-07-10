# HP Refresh Automation
Automating the refresh of HP Desktop Mini PCs — including inventory collection, secure cleanup, imaging preparation, and post-deployment configuration.

---

## 📦 Project Overview

This repository was designed to streamline large-scale IT refresh operations by automating repetitive tasks during the replacement of aging HP Desktop Mini PCs. It includes PowerShell scripts and templates used during enterprise refresh projects to improve consistency, speed, and auditability.

---

## 🧰 Features

- ✅ Inventory collection (serial number, model, asset tag, assigned user)
- ✅ Pre-imaging cleanup (removal of bloatware or legacy software)
- ✅ Post-deployment configuration (hostname, user assignment, domain rejoin)
- ✅ Asset tracking templates for auditing and ticket documentation

---

## 📁 Folder Structure

hp-refresh-automation/
├── scripts/
│ ├── inventory-collector.ps1
│ ├── cleanup-uninstall.ps1
│ ├── post-refresh-config.ps1
├── templates/
│ └── asset-tag-template.csv
├── logs/
├── README.md
└── LICENSE  

> `logs/` is optional and used to store output or error reports during execution.

---

## 📜 License

Licensed under the MIT License. Feel free to use and modify this project with attribution.

---

## 👤 Author

**Matt Johns**  
IT Systems Technician | Field Support | Automation Specialist  
📍 Sacramento, CA  
🔗 [github.com/trstnrsk](https://github.com/trstnrsk)
