# Innovation Village  
### A Scalable AI-Driven Multi-Agent Automation Framework

---

## 🚀 Overview

Innovation Village is a modular AI-powered automation framework designed to modernize operational workflows using conversational intelligence and structured automation.

The system integrates AI agents, workflow automation (n8n), Google Sheets as a structured data layer, and real-time dashboard visualization to create a unified operational intelligence ecosystem.

Rather than building isolated applications, this project demonstrates a scalable, extensible multi-agent architecture engineered for clarity, automation, and future expansion.

---

## ❓ Why Innovation Village?

Traditional business operations rely heavily on manual spreadsheets, fragmented communication, and reactive decision-making.

Innovation Village reimagines operations using conversational AI and automation-first workflows, transforming static systems into intelligent, self-operating ecosystems.

---

## 🏗️ System Architecture

The framework follows a **Layered Intelligence Architecture**:

1. **User Interaction Layer**  
   Conversational chat interfaces and dashboard UI for natural input.

2. **AI Decision Engine**  
   OpenAI-powered agents interpret user intent and determine required actions.

3. **Automation Engine**  
   n8n workflows orchestrate structured execution logic.

4. **Data Layer**  
   Google Sheets serves as a structured operational database.

5. **Dashboard Visualization**  
   Lovable UI dashboards provide real-time analytics and insights.

This separation ensures modularity, maintainability, and scalability.

---

## 🏗️ High-Level Architecture

User Interface
↓
AI Decision Engine
↓
n8n Automation Layer
↓
Google Sheets (Data Layer)
↓
Lovable Dashboard


---

## 🤖 Multi-Agent Ecosystem

The current implementation includes multiple specialized AI agents:

### 🧠 Main Agent (Orchestrator)
- Delegates tasks to appropriate sub-agents  
- Manages overall workflow coordination  

### 📦 Stock Manager Agent
- Conversational inventory management  
- Add / update / delete stock records  
- Low-stock detection  
- Real-time data sync with dashboard  

### 📊 Project Manager Agent
- Conversational project updates  
- Status tracking & revenue monitoring  
- Client database handling  
- Automated email notifications  

### 📧 Gmail AI Reply Agent
- Auto-labels incoming emails  
- Drafts structured HTML responses  
- Uses AI-based intent classification  

### 🎨 UGC Image AI Agent
- Image analysis using Gemini  
- AI-generated image prompt engineering  
- Automated image generation workflow  
- Casual UGC-style rendering logic  

### 🧠 Sub Agent (Email Automation)
- Executes delegated workflow tasks  
- Handles automated structured email communication  

---

## 💡 Core Design Principles

### 1️⃣ Conversational-First Design
Users interact naturally using chat instead of manual spreadsheet manipulation.

### 2️⃣ Automation-Centric Execution
n8n workflows ensure structured CRUD operations and controlled data updates.

### 3️⃣ Modular Intelligence
Each agent operates independently yet integrates seamlessly.

### 4️⃣ Extensible Multi-Agent Vision
The architecture supports seamless addition of:
- Analytics Agent  
- Monitoring Agent  
- Reporting Agent  
- Predictive AI Modules  

---

## 🛠️ Technology Stack

| Layer | Technology |
|-------|------------|
| Automation Engine | n8n |
| AI Models | OpenAI (GPT-4o mini), Gemini |
| Data Storage | Google Sheets |
| Dashboard | Lovable |
| Email Integration | Gmail API |
| Image Generation | FLUX API |
| Memory Handling | n8n Memory Modules |

---
## ⚙️ Setup Instructions

### 1️⃣ Install n8n Locally

```bash
npm install n8n -g
n8n


Or use Docker.

2️⃣ Import Workflows

Open n8n

Import JSON files from /workflows

Reconnect credentials manually

3️⃣ Configure Credentials

OpenRouter API

Google Sheets OAuth

Gmail OAuth

Image API keys

4️⃣ Activate Workflows

## 🔄 Workflow Execution Flow
User Message
      ↓
AI Agent Interpretation
      ↓
Tool Selection
      ↓
Google Sheets / Gmail / Image API Execution
      ↓
Dashboard Update
      ↓
Operational Insight

## 📈 Impact

Reduced manual coordination

Real-time operational visibility

Automated communication workflows

Improved decision-making efficiency

Structured AI-driven automation

## 🚀 Future Roadmap

AI-based stock forecasting

Predictive project timeline estimation

Role-based access control

PostgreSQL migration

Advanced analytics agent

Monitoring & reporting agents

## 👥 Team

Vala Nirav
Co-Founder & AI Automation Architect

System architecture design

n8n workflow engineering

AI orchestration logic

Automation structuring

Shruti Soni
Co-Founder & AI Systems Developer

AI agent development

Prompt engineering

Dashboard integration

Image automation workflows

This system was co-architected and developed with equal contribution by both team members.

 ##📌 Current Status

🚧 Active Development
🧠 Multi-Agent Framework (Phase 1 Complete)

## 📂 Repository Structure
innovation-village/
│
├── workflows/        # n8n workflow JSON files
├── dashboard/        # Lovable frontend code
├── docs/             # Documentation (optional)
└── README.md

## 🌱 Vision

Innovation Village is not just a collection of workflows —
it is a unified AI-driven automation framework engineered for scalable operational intelligence.

The system demonstrates how conversational AI, structured automation, and real-time analytics can converge into a cohesive multi-agent ecosystem.
