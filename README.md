# ☁️ OpenStack Service Deployment & Automation with Ansible

This project provides a complete automation solution for deploying, operating, and cleaning up services within an **OpenStack Cloud** environment. It combines CLI scripting and **Ansible playbooks** to manage the entire lifecycle of a cloud-based service deployment.

---

## 🧠 Why This Project?

- 📦 Automates VM provisioning and teardown on OpenStack
- ⚙️ Uses Ansible + Bash to orchestrate cloud service lifecycle
- 🧹 Includes install, operate, and cleanup stages
- 🔐 Handles SSH key creation and cloud authentication via openrc files

---

## 🔧 Tech Stack

- **Python 3**
- **Ansible**
- **OpenStack CLI** (version 5.2.0)
- **Bash / Shell scripting**
- **jq** (for JSON parsing)
- **SNMP** (optional monitoring)

---
## ⚙️ Getting Started

### 🔑 Prerequisites

- Python 3.6+
- `pip`, `jq`, `snmp`
- OpenStack CLI tools (v5.2.0)
- Ansible installed:  
  ```bash
  pip install ansible

