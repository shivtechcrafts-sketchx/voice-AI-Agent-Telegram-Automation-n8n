# voice-AI-Agent-Telegram-Automation-n8n

.

🎥 Demo (Proof of Work)
https://drive.google.com/file/d/1H4taVKy4s_FNKvQS6sj2ww83GXfn2gI2/view?usp=sharing

---

🔊 Voice AI Agent for Telegram (n8n Automation)

📌 Project Summary

This project demonstrates my ability to design and deploy real-world AI automations using n8n.

I built an AI-powered Voice Assistant that integrates with Telegram to:

Read unread messages

Convert text messages into voice responses

Send voice replies back to users

Trigger email notifications for unread messages


The focus of this project is automation architecture, API integration, and AI workflow orchestration — not just theory.


---

🎯 Why This Project Matters 

This project showcases:

✅ Practical automation (not toy scripts)

✅ Event-driven workflows

✅ API integrations (Telegram, Email, AI/TTS)

✅ Production-style credential handling

✅ Real user-facing output (voice + messaging)


This is the kind of system used in customer support bots, accessibility tools, and notification agents.


---

🧠 What I Built (Core Capabilities)

Telegram Bot Listener

Detects incoming and unread messages


AI Voice Generation

Converts text → speech using AI services


Bidirectional Communication

Sends voice replies back to Telegram


Email Automation

Sends alerts when messages remain unread


Fully Automated Workflow

Runs without manual intervention once activated




---

🛠️ Tech Stack

Component	Technology

Automation Engine	n8n
Messaging	Telegram Bot API
AI / Voice	Text-to-Speech (TTS) AI
Notifications	Email (SMTP/Gmail)



---

🏗️ System Architecture (High-Level)

1. Telegram message received


2. n8n webhook triggers workflow


3. Message status checked (read / unread)


4. Text processed by AI → voice


5. Voice message sent to Telegram


6. Unread messages trigger email alerts



This architecture is modular, extensible, and production-friendly.


---

📂 Repository Structure

📦 voice-ai-telegram-agent
 ┣ 📜 workflow.json        # Exported n8n workflow
 ┣ 📸 screenshots/         # Workflow & execution screenshots
 ┣ 📄 README.md            # Documentation


---

⚙️ Setup & Usage

1. Clone the repository


2. Import workflow.json into n8n


3. Configure credentials:

Telegram Bot Token

AI / TTS API Key

Email SMTP credentials



4. Activate the workflow



> ⚠️ API keys are intentionally excluded for security reasons




---

📸 Screenshots

Workflow and execution screenshots are available in the /screenshots folder to clearly show:

Node configuration

Data flow

Output messages



---

🔒 Security & Best Practices

No credentials committed to the repository

Uses n8n credential management

Bot privacy mode handled correctly


This follows basic production hygiene, not hobby-level shortcuts.


---

📈 Possible Extensions (Future Scope)

WhatsApp integration

Voice language detection

Priority-based message handling

Dashboard for message analytics



