# 🤖 AI News Summarizer Workflow (n8n + Gemini)

An automated AI-powered workflow that collects the latest Artificial Intelligence news from multiple sources, summarizes them using Google Gemini, and sends a structured email digest daily.

---

## 🚀 Project Overview

This project uses **n8n automation** to create a fully automated AI news pipeline:

✔ Fetches AI news from RSS feeds
✔ Aggregates articles from multiple sources
✔ Uses Google Gemini to summarize news
✔ Formats as an email digest
✔ Sends daily updates automatically

---

## 🧠 Workflow Steps

### ⏰ Schedule Trigger

Runs automatically every day at 10 AM.

### 📰 News Collection

Sources used:

* AI Business RSS feed
* TechCrunch AI category
* Event data via API

### 🔀 Merge & Aggregate

Combines all collected news into one dataset.

### 🤖 AI Summarization

Google Gemini generates:

* Headlines in CAPS
* Short summaries
* Article links
* Email-ready format

### 📧 Email Delivery

Automatically sends summarized AI news to the user.

---

## 🛠️ Technologies Used

* n8n (Workflow Automation)
* Google Gemini API (AI)
* RSS Feeds
* SerpAPI
* Gmail API

---

## ⚙️ How to Use

1. Import the workflow JSON into n8n
2. Add your API credentials
3. Activate the workflow

---

## 👩‍💻 Author

**Meghana K R**
B.E. Computer Science & Design
AI & Automation Enthusiast

---

## ⭐ Why This Project Matters

Demonstrates skills in:

* AI Integration
* Automation
* API Handling
* Real-world Workflow Design
