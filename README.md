# 🏛️ Sarkari Job Alert Bot

AI-powered Government Job Alert Bot that scrapes 5 govt job portals daily, 
filters CS/IT relevant jobs using Groq LLaMA, and sends Telegram alerts.

## 🛠️ Tech Stack
- **n8n** — Automation engine
- **Groq LLaMA 3.3 70B** — AI job filter
- **Telegram Bot** — Job alerts
- **Google Sheets** — Deduplication storage
- **Render** — Free cloud hosting

## ⚙️ How It Works
1. Fetches jobs from 5 RSS feeds daily at 8AM
2. AI filters only CS/IT relevant jobs
3. Sends Telegram alert for relevant jobs
4. Saves all jobs to Google Sheets

## 📊 Workflow
![Workflow](workflow.png)
