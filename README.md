# AI Token Calculator for Genesys Cloud CX

Estimate AI token usage for Genesys Cloud CX based on different AI capabilities, interaction volumes, and architectural choices.

---

## 📌 Overview

This repository provides simple, practical calculators to estimate **Genesys Cloud AI token consumption and cost** across different use cases, including:

- Voice & Digital Bots  
- Virtual Agents  
- Agentic Virtual Agents  
- AI Guides  
- AI Summaries, Translate, Scoring  
- Copilot & Analytics  
- Messaging & Predictive Engagement  

The goal is to support:
- Solution design discussions  
- Pre-sales estimations  
- Internal alignment between technical and business teams  

---

## ⚙️ Available Calculators

| Calculator | Description |
|-----------|------------|
| **USD Calculator** | Estimates cost in USD |
| **EUR Calculator** | Estimates cost in EUR (€0.80/token assumption) |

👉 Open the calculators from the main page:

---

## 🧠 How to Use

1. Enter expected monthly volumes:
   - interactions
   - sessions
   - users
   - events

2. Adjust AI usage assumptions:
   - % of interactions using Virtual Agent  
   - % using Agentic Virtual Agent  
   - containment rates  

3. Review:
   - token consumption
   - estimated monthly cost
   - distribution across AI services  

---

## 🧩 Key Concepts (Simplified)

### Bots
- Traditional structured flows (Architect / Dialog Engine)
- Charged by minutes (voice) or sessions (digital)

### Virtual Agent
- AI-enhanced bot experience
- More natural conversation, knowledge integration
- Charged per session

### AI Guides
- AI Studio assets defining conversational logic
- From May 14, 2026:
  - no cost for creation
  - part of Virtual Agent experience

### Agentic Virtual Agent
- Advanced AI agents with reasoning, tools, and autonomy
- Charged per session (higher tier)

---

## 💡 Important Billing Principle

> If multiple AI capabilities are used in one interaction, billing is based on the **highest-level AI resource used**.

This makes architecture decisions directly impact cost.

---

## 📅 Pricing Assumptions

This simulator reflects **May 14, 2026 pricing model updates**, including:

- Agentic Virtual Agent → **1.2 tokens per session**
- Virtual Agent → **2 sessions per token**
- AI Guides → **no token cost for creation**
- EUR pricing → **€0.80 per token (assumed)**

---

## ⚠️ Disclaimer

This is an **unofficial estimation tool** based on publicly available documentation and practical interpretation.

- Not a replacement for official pricing
- Not a contractual reference
- Always validate with Genesys AE / official documentation

---

## 🏗️ Repository Structure
/
├── index.html
├── README.md
├── TokenPrice-USD/
│ └── index.html
└── TokenPrice-EUR/
└── index.html

---

## 🎯 Purpose

This tool is designed for:

- Solution Architects  
- Pre-sales engineers  
- Business Development teams  
- Partners working with Genesys Cloud CX  

---

## 🚀 Future Improvements (optional ideas)

- Toggle between current vs future pricing
- Scenario presets (banking, telco, retail)
- Visual charts (token distribution)
- Integration with real usage data

---

## 🤝 Contributions

Feel free to adapt and extend this calculator for your own use cases.

---

## 🧑‍💻 Author

Prepared as a practical tool for working with Genesys Cloud CX AI capabilities.

