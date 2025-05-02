# 🤖 Alice — Smart CS Agent for Skincare Brand (n8n + OpenAI)

Alice is an AI-powered customer service agent built using **n8n**, **OpenAI**, and **Google Sheets**.  
Designed for skincare and fashion brands to handle common customer inquiries, reduce manual support time, and escalate only when needed.

---

## 🧠 Features

- Responds to FAQs using brand knowledge base
- Recommends products based on skin condition
- Calculates estimated shipping (via tool)
- Logs all interactions to Google Sheets
- Gracefully rejects irrelevant questions
- Sends alert to admin if stuck

---

## 🧩 Tech Stack

- [x] n8n (workflow engine)
- [x] OpenAI (GPT-4o via LangChain)
- [x] Google Sheets API
- [x] Gmail API (alert routing)
- [x] Modular, scalable workflow design

---

## 🧱 Workflow Structure

1. **Trigger:** Webhook / Chat source
2. **Cleaner:** Normalize input
3. **Prompt Builder:** Inject brand context
4. **AI Agent:** Answer using tools + memory
5. **IF Node:** Detect fallback / edge case
6. **Logger:** Save to Google Sheets
7. **Gmail:** Escalate to human

---

## 🏁 Built by Neura Forge

This agent is part of **Neura Forge’s AI agent suite** — helping small business owners multiply their profit using automation and AI systems.

Let’s build your custom AI agent.  
➡️ [Connect on LinkedIn][(https://www.linkedin.com/in/yourusername) ](https://www.linkedin.com/in/bheta-dwiki-maranata-15654b227/) 
