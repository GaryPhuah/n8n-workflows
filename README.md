# n8n-workflows

**Library of n8n workflows — starting with chatbots, expanding into diverse automation.**  
This repository contains ready-to-use n8n workflows in JSON format, which can be imported into your n8n instance and customized to your needs.

---
## Overview

The workflows in this repository are currently focused on **chatbot automation**, including:
- Email chatbot automation
- Web chatbot automation
- WhatsApp chatbot automation
- Telegram chatbot automation
- Knowledge Base upload workflows (For all apps)

**Coming soon:** Additional workflows for integrations, data processing, and general automation tasks.

---

## Folder Structure
```
n8n-workflows/
│
├── chatbot-automations/
│ ├── Email Chatbot Automation (KB).json
│ ├── Web Chatbot Automation (KB).json
│ ├── WhatsApp Chatbot Automation (KB).json
│ ├── Telegram + Mail Chatbot Automation (KB).json
│ ├── Telegram Chatbot Automation (KB).json
│ ├── Upload Knowledge Base (M1).json
│ ├── Upload Knowledge Base (M2).json
│
└── README.md
```
---

## Getting Started
### Prerequisites
- [n8n](https://n8n.io) v1.0 or newer
- API keys and credentials for relevant platforms (Email, WhatsApp, Telegram)
- A configured Knowledge Base (support all types of file formats) or connected data source

### Installation
1. **Install n8n** using npm:
   ```bash
   npm install n8n -g
   ```
   Or follow the n8n installation guide [official n8n installation guide](https://docs.n8n.io/getting-started/installation/)

2.**Importing a Workflow**
Open your n8n dashboard.
Go to Workflows → Import from File.
Select the desired .json file.
Update any required environment variables, API keys, or webhook URLs


## Notes
These workflows are templates — you may need to adapt them to your specific setup.
You are free to modify, combine, or extend these workflows for your own use cases.
