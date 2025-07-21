# n8n-replit-docker-
This project lets you run n8n on Replit using Docker with zero server costs. It's perfect for solopreneurs, indie hackers, or no-code builders who want to launch automations, SaaS APIs, or GPT-powered workflows without needing expensive cloud infrastructure.
# 🚀 n8n on Replit with Docker (Zero-Cost Setup)

Run your own free, self-hosted **n8n automation server** using **Docker on Replit** — perfect for building micro-SaaS tools, AI agents, or custom APIs with no cloud cost.

---

## ✅ Features

- 📦 Runs official `n8n` in Docker
- 🧠 Perfect for workflows, webhooks, and AI integrations
- 🆓 100% free hosting using Replit (with Docker)
- 🔁 Use with UptimeRobot to stay always-on
- 🔐 Secure with basic auth

---

## 🔧 Setup Instructions

### 1. Fork This Repo
Click the **“Fork”** button on GitHub to copy this repo to your account.

### 2. Import into Replit
Go to [https://replit.com](https://replit.com) → Click **“Create Repl” → “Import from GitHub”** → Paste your forked repo URL.

### 3. Add Secrets (Environment Variables)
Click the **“Secrets”** tab in Replit and add:

| Name | Value |
|------|-------|
| `N8N_BASIC_AUTH_ACTIVE` | `true` |
| `N8N_BASIC_AUTH_USER` | yourusername |
| `N8N_BASIC_AUTH_PASSWORD` | yourpassword |
| `N8N_HOST` | `0.0.0.0` |
| `N8N_PORT` | `5678` |

> You can also copy `.env.example` and rename it to `.env` (optional for local testing).

---

### 4. Run It 🚀
- Click the **“Run”** button in Replit.
- Wait ~60–90 seconds while Docker installs and launches n8n.
- Your public URL will look like:
https://n8n--yourusername.repl.co

---

## ⏰ Keep n8n Always Online

Use [https://uptimerobot.com](https://uptimerobot.com) to ping your Replit URL every 5 minutes.

1. Create a free account
2. Add a new **HTTP(s) monitor**
3. Paste your Replit n8n URL
4. Set interval to **every 5 minutes**

---

## 🧠 Example Use Cases

- ✨ AI-powered meeting summarizer
- 📧 Email auto-responder SaaS
- 🗓️ Google Calendar assistant
- 📊 Form-to-Spreadsheet automation

---

## 💡 Credit

Created with ❤️ by [Sayyam Anand](https://github.com/SayyamAnand).  
Inspired by the n8n community and open-source automation builders.

---

## 📜 License

MIT License. Based on n8n's [Fair Code License](https://github.com/n8n-io/n8n/blob/master/LICENSE.md).
