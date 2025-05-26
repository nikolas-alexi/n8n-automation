# n8n-automation

This project is a **real estate automation workflow built 100% in n8n**, designed to assist real estate agents in qualifying leads and streamlining communication with potential sellers and buyers.

> ⚡️ Entirely built as a personal project — tested, improved, and structured by Nikolas Alexi using his own logic and creativity.

## 🔍 Overview

The automation receives lead data and decides what path to follow depending on the user's interest:

- **No interest yet?** → Sends an SMS to inform that a real estate agent will reach out soon and marks the lead for manual follow-up.
- **Interested client?** → Identifies the property type and forwards the lead to the correct agent.
- If the property is an apartment, it triggers a personalized message workflow with ChatGPT.

## 🧠 Tools & Integrations

- [n8n](https://n8n.io): Core workflow builder.
- **Gmail**: Used to notify real estate agents and communicate with leads.
- **Supabase**: Stores data collected from leads.
- **ChatGPT (OpenAI)**: Finalizes messages to potential sellers based on their interest and property type.

## 📌 Key Highlights

- Decision-making flow using simple `if` nodes to handle dynamic routing.
- Use of ChatGPT to personalize and polish outgoing messages.
- Designed for **property qualification** and routing leads to proper agents.

## 🧪 Status

> ✅ Project completed as a **personal learning challenge**.  
> 🛠️ Still not in production — made for testing workflows, logic structuring, and tool integration.

---

Built with 💡 by **Nikolas Alexi**  
Passionate about no-code, automation, and helping businesses become more efficient with smart workflows.
