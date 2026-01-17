# Caledonian Shield 🛡️

AI-powered security & compliance companion (UK-focused) — phishing analysis, log explanation, and compliance mapping.

## 🚀 Live Demo
- PartyRock App: <(https://partyrock.aws/u/Hackathon2025/cDeTQkxCo/Caledonian-Shield)>

## 🧪 Example Usage
Use **sanitised** examples only (no passwords, tokens, or personal data).

- Paste suspicious email/SMS text → get risk score + red flags + next steps  
- Paste a log line → get explanation + severity + investigation guidance  
- Select compliance category → get practical UK-focused recommendations
- 
## 🔥 Features
### UK Scam & Phishing Detector
- Analyses suspicious content (email, SMS, WhatsApp)
- Provides a risk score + red flags + recommended actions

### AI SOC Assistant (Junior Analyst Support)
- Explains security logs in plain English
- Highlights likely causes, severity, and investigation steps
- Designed for learning and triage-style reasoning

### UK Compliance Guide
- UK GDPR / data protection awareness
- Practical guidance for individuals and small organisations
- Helps map issues to common compliance themes

## 🧠 Tech Stack
- AWS PartyRock (UI)
- AWS Bedrock (LLM inference)
- Whiskers (agent/prompt workflow)

## 📚 Documentation
- Architecture: `docs/architecture.md`
- Threat Model: `docs/threat-model.md`

## 🧩 Prompt Templates
- `prompts/phishing_analysis.md`
- `prompts/log_explainer.md`
- `prompts/uk_compliance_mapper.md`

## 🔐 Security & Data Handling
This repository contains **no secrets** and **no credentials**.

All examples are **sanitised** and intended for educational/demo purposes only.

## 📌 Roadmap
- Add MITRE ATT&CK mapping
- Add Wazuh-style sample log packs
- Export report-style outputs (SOC notes format)
