# ai-ticket-routing-system
Ai-powered customer support ticket routing using Gemini + n8n + Gmail automation
# 🚀 AI Ticket Routing System (n8n + Gemini AI)

## 📌 Overview
An AI-powered automation system that classifies customer support tickets and routes them to the correct department automatically using n8n workflows and Google Gemini AI.

---

## 🎯 Problem Statement
Manual ticket handling causes delays and misrouting. This system automates:
- Ticket classification
- Department routing
- Email notification

---

## ⚙️ System Architecture

Customer Form → Google Gemini AI → Switch Node → Gmail Automation

---

## 🧠 AI Features
- Ticket classification:
  - Support
  - Engineering
  - Finance
- Priority detection: High / Medium / Low
- Sentiment analysis
- Structured JSON output

---

## 🛠 Tech Stack
- n8n (Workflow automation)
- Google Gemini API
- Gmail API
- JSON parsing
- Switch-based routing logic

---

## 📧 Example Output

Input:
"I was charged twice for my subscription"

Output:
- Category: Finance  
- Department: Finance  
- Priority: High  
- Sentiment: Negative  

---

## 🚀 Live Status
✔ Workflow is deployed and active using n8n automation

---

## 🔥 Future Improvements
- Auto Ticket ID generation (TCK-0001)
- Google Sheets database logging
- Slack notifications for Engineering
- SLA escalation system
