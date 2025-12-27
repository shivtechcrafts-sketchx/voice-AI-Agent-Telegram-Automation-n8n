# <p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=30&duration=3000&pause=700&color=00E5FF&center=true&vCenter=true&width=1000&lines=Voice+AI+Agent+for+Telegram;Built+with+n8n+Automation;Text+to+Speech+%7C+Event+Driven+AI;Production+Ready+Workflow" />
</p>

![WhatsApp Image 2025-12-22 at 11 02 59 PM](https://github.com/user-attachments/assets/f7f801cf-8bfb-475c-86c6-d1b231f0af1c)

🎥 Demo (Proof of Work)
https://drive.google.com/file/d/1H4taVKy4s_FNKvQS6sj2ww83GXfn2gI2/view?usp=sharing

# Demo Of the Output

<img width="1920" height="1080" alt="Screenshot 2025-12-27 114538" src="https://github.com/user-attachments/assets/bf5a2b3a-1dfb-4cbb-bf72-4d6b95251243" />

---

# 🔊 Voice AI Agent for Telegram (n8n Automation)

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=30&duration=3000&pause=700&color=00E5FF&center=true&vCenter=true&width=1000&lines=Voice+AI+Agent+for+Telegram;Built+with+n8n+Automation;Text+to+Speech+%7C+Event+Driven+AI;Production+Ready+Workflow" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Automation-n8n-ff6d00?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Telegram-Bot-229ED9?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AI-Text--to--Speech-00e5ff?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Workflow-Event--Driven-success?style=for-the-badge" />
</p>

<p align="center">
  <img src="screenshots/telegram-demo.gif" width="70%" alt="Telegram Voice AI Demo" />
</p>

---

## 🚀 Project Overview

This project demonstrates a **real-world Voice AI Automation system** built using **n8n** and the **Telegram Bot API**.

It listens to Telegram messages, processes them using AI, converts responses into **voice messages**, and sends them back automatically. If messages remain unread, the system escalates via **email notifications**.

This repository reflects **production-style automation architecture**, not a toy or tutorial workflow.

---

## 🎯 Why This Project Matters

✅ Designed like real automation used in companies
✅ Event-driven (no manual triggers)
✅ Multiple APIs orchestrated cleanly
✅ Secure credential handling (no secrets in code)
✅ Human-facing output (voice replies)

Typical real-world use cases:

* Customer support voice bots
* Accessibility assistants
* Alert & monitoring agents

---

## 🧠 Core Capabilities

### 🤖 Telegram Bot Listener

* Receives incoming Telegram messages
* Identifies unread messages

<p align="center">
  <img src="screenshots/telegram-input.png" width="80%" />
</p>

---

### 🔊 AI Voice Generation

* Processes text using AI
* Converts responses into natural voice output

<p align="center">
  <img src="screenshots/tts-node.png" width="80%" />
</p>

---

### 🔁 Bidirectional Communication

* Text input → Voice output
* Voice message delivered back to Telegram automatically

<p align="center">
  <img src="screenshots/telegram-voice-output.gif" width="70%" />
</p>

---

### 📧 Email Automation

* Sends email alerts if messages remain unread
* Useful for monitoring and escalation

<p align="center">
  <img src="screenshots/email-alert.png" width="80%" />
</p>

---

### ⚙️ Fully Automated Workflow

* Runs continuously once activated
* No human intervention required

---

## 🛠️ Tech Stack

| Layer             | Technology              |
| ----------------- | ----------------------- |
| Automation Engine | n8n                     |
| Messaging         | Telegram Bot API        |
| AI / Voice        | Text-to-Speech (TTS AI) |
| Notifications     | Email (SMTP / Gmail)    |

---

## 🏗️ System Architecture

<p align="center">
  <img src="screenshots/architecture-diagram.png" width="85%" />
</p>

```text
Telegram Message
      ↓
 n8n Webhook Trigger
      ↓
 Message Status Check
      ↓
 AI Text Processing
      ↓
 Text → Voice (TTS)
      ↓
 Telegram Voice Reply
      ↓
 (If Unread) → Email Alert
```

Modular, extensible, and production-friendly.

---

## 📂 Repository Structure

```text
📦 voice-ai-telegram-agent
 ┣ 📜 workflow.json        # Exported n8n workflow
 ┣ 📸 screenshots/         # UI, nodes & execution demos
 ┣ 📄 README.md            # Documentation
```

---

## ⚙️ Setup & Usage

1. Clone this repository
2. Import `workflow.json` into **n8n**
3. Configure credentials:

   * Telegram Bot Token
   * AI / TTS API Key
   * Email SMTP credentials
4. Activate the workflow

⚠️ API keys are intentionally excluded for security reasons

---

## 🔒 Security & Best Practices

* No secrets committed to GitHub
* Uses n8n credential manager
* Telegram privacy mode enabled
* Clean separation of logic & credentials

---

## 📈 Future Enhancements

* WhatsApp voice automation
* Automatic language detection
* Priority-based message routing
* Analytics dashboard for message insights

---

## 👤 Author

**Shiv**
Automation Engineer • AI Agents • Workflow Orchestration

<p align="left">
  <img src="https://skillicons.dev/icons?i=js,nodejs,python,telegram,github" />
</p>

---

⭐ If you care about real automation and AI systems, star this repository.
