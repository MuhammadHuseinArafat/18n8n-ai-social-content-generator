# 18n8n-ai-social-content-generator

# Project 18: AI-Powered Social Media Content & Hashtag Generator Automation

## 📋 Business Problem
Content creators, digital marketers, and business owners spend hours brainstorming ideas, drafting copy, structuring hooks, and researching trending hashtags for daily social media publications. Manual content creation creates bottlenecks and limits posting consistency.

## 💡 Proposed Solution
Engineered an **AI-Driven Content Creation Engine** in n8n leveraging Google Gemini. The system automatically ingests short raw topic inputs, processes them through specialized creative copywriting prompts, generates structured multi-part LinkedIn/social posts (complete with Hooks, Body Content, CTAs, and Hashtags), and instantly dispatches the final draft to private messaging channels.

## 🛠️ Architecture & Flow
1. **Trigger & Input:** Captures short raw topic descriptions via a simulated input node.
2. **AI Processing Layer (`Basic LLM Chain` + `Google Gemini`):** Deploys specialized system instructions to transform simple ideas into ready-to-publish professional copywriting outputs.
3. **Automated Delivery (`Telegram Node`):** Delivers the structured copy instantly to the creator's chat for quick review and publishing.

## 🧰 Tools & Nodes Used
- **Platform:** n8n
- **AI Model:** Google Gemini Chat Model (`models/gemini-3-flash-preview`)
- **n8n Nodes:** Manual Trigger, Edit Fields (Set), Basic LLM Chain, Telegram (Send Message).

  <img width="851" height="357" alt="image" src="https://github.com/user-attachments/assets/88f7814d-2b65-480d-92a8-1d082bcc139c" />


## 🚀 Business Value & Impact
- **Content Velocity:** Cuts content drafting time from hours to mere seconds.
- **Consistency & Quality:** Ensures every published post follows proven engagement structures (Hook-Body-CTA).
