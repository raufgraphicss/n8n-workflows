# 🚀 Mega n8n Workflow Collection: 2,000+ Automation Templates

![n8n](https://img.shields.io/badge/n8n-Low--Code-FF6D5B?style=for-the-badge&logo=n8n)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)
![Workflows](https://img.shields.io/badge/Workflows-2000+-green?style=for-the-badge)
![GitHub Stars](https://img.shields.io/github/stars/YOUR_USERNAME/YOUR_REPO_NAME?style=for-the-badge)


Welcome to the **largest open-soure repository of n8n workflows** on GitHub! This collection features over **2,000+ production-ready workflows** designed to automate everything from simple daily tasks to complex enterprise-level business processes.

Whether you are an automation engineer, a business owner, or a hobbyist, this library provides a plug-and-play foundation for your n8n instance.

---

## 📖 Table of Contents
- [Project Overview](#-project-overview)
- [Workflow Categories](#-workflow-categories)
- [How to Use These Workflows](#-how-to-use-these-workflows)
- [Directory Structure](#-directory-structure)
- [Key Features](#-key-features)
- [Security & Best Practices](#-security--best-practices)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🌟 Project Overview

Automating workflows can be time-consuming. This repository aims to eliminate the "blank canvas" anxiety by providing 2,000+ JSON templates. Each workflow is organized by category and includes standard naming conventions to help you find exactly what you need.

> **Goal:** To empower the low-code community with ready-to-use automation logic for AI, CRM, Social Media, DevOps, and more.

---

## 📂 Workflow Categories

The workflows are divided into specialized directories. Here is a glimpse of what you will find:

| Category | Description | Key Integrations |
| :--- | :--- | :--- |
| **🤖 AI & Machine Learning** | LLM chains, autonomous agents, and image gen. | OpenAI, Anthropic, LangChain, Pinecone |
| **📈 Marketing & CRM** | Lead generation, email sequences, and CRM sync. | HubSpot, Salesforce, Mailchimp, Pipedrive |
| **📱 Social Media** | Auto-posting, sentiment analysis, and tracking. | Instagram, Twitter, LinkedIn, TikTok API |
| **💼 Business Operations** | Invoicing, document management, and HR bots. | Google Drive, Notion, Slack, Microsoft 365 |
| **🛠️ DevOps & IT** | Server monitoring, GitHub actions, and backups. | Docker, AWS, Cloudflare, DigitalOcean |
| **🛒 E-commerce** | Order tracking, cart recovery, and inventory. | Shopify, WooCommerce, Stripe, PayPal |
| **📊 Data Science** | Web scraping, data cleaning, and reporting. | PostgreSQL, MySQL, Google Sheets, AirTable |
| **🏠 Personal Productivity** | Calendar sync, smart home, and daily digests. | Todoist, Telegram, Apple Health, Spotify |

---

## 🚀 How to Use These Workflows

Using these templates is incredibly easy. No coding skills are required!

### Option 1: Copy-Paste (Recommended)
1. Navigate to the folder of your choice and open the `.json` file.
2. Copy the entire content of the file.
3. Open your **n8n Editor**.
4. Press `CMD/CTRL + V` (Paste) directly onto the canvas.
5. Configure your specific credentials (API keys, etc.) in the nodes.

### Option 2: Bulk Import
1. Clone this repository: 
   ```bash
   git clone [https://github.com/raufgraphicss/n8n-workflows](https://github.com/raufgraphicss/n8n-workflows)

```

2. Use the n8n CLI or the `n8n-import` tool to upload multiple workflows to your self-hosted instance.

---

## 🏗 Directory Structure

To keep the repository clean, we follow a strict hierarchical structure:

```text
.
├── workflows/
│   ├── 01-AI-Automation/
│   │   ├── openai-summarizer.json
│   │   └── langchain-agent-search.json
│   ├── 02-Marketing-CRM/
│   │   ├── hubspot-to-google-sheets.json
│   │   └── lead-nurturing-email-sequence.json
│   ├── ... (and 20+ more categories)
├── scripts/                # Helper scripts for bulk operations
├── docs/                   # Detailed documentation for complex workflows
├── LICENSE
└── README.md

```

---

## ✨ Key Features

* **Standardized Nodes:** Every workflow uses the latest version of n8n nodes.
* **Error Handling:** Most complex workflows include error-trigger nodes to ensure reliability.
* **Annotated Canvas:** Sticky notes are added inside the JSON to explain the logic of each step.
* **Optimized Performance:** Workflows are built to minimize memory usage and execution time.
* **Lightweight:** No heavy dependencies—just raw JSON files.

---

## 🔒 Security & Best Practices

1. **Credentials:** **IMPORTANT!** All JSON files in this repo are exported *without* credentials. You must add your own API keys, OAuth tokens, or passwords.
2. **Environment Variables:** For sensitive data, we recommend using n8n expressions with environment variables.
3. **Review Before Execution:** Always inspect the logic of a workflow before activating it to ensure it aligns with your data privacy policies.

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place! If you have a workflow you'd like to share:

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingWorkflow`).
3. Commit your Changes (`git commit -m 'Add some AmazingWorkflow'`).
4. Push to the Branch (`git push origin feature/AmazingWorkflow`).
5. Open a Pull Request.

---

## 📜 License

Distributed under the **MIT License**. See `LICENSE` for more information. This means you can use, modify, and distribute these workflows for personal or commercial projects.

---

## ☕ Support This Project

If these 2,000+ workflows saved you hundreds of hours of work, consider:

* ⭐️ Starring this repository.
* 🔱 Forking it for your own use.
* 🐦 Sharing it on Twitter/LinkedIn to help others.

---

## 📬 Contact

**Rauf Babayev** - [@raufgraphicss](https://www.google.com/search?q=https://instagram.com/raufgraphicss) - raufmediya@gmail.com

**Made with human and 🤖 for the n8n Community.**
