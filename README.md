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
- Improve UI/UX: simplify navigation and reduce cognitive overload (focus on fewer core tools per screen)
- Split features into modules: Phishing / SOC Logs / Compliance (separate tabs or separate pages)
- Add “Environment Builder” to tailor outputs (OS, business type, tools used, risk level)
- Add verbosity controls: Quick Summary / Detailed SOC View / Step-by-Step Beginner Mode
- Reduce repeated static generation by caching “static guidance” and only generating personalised sections
- Add structured outputs: risk score, confidence level, recommended next actions, and severity rating
- Add MITRE ATT&CK mapping for detected behaviours and log patterns
- Add Wazuh-style sample log packs + parsing templates for common alert types
- Add exportable incident notes (SOC report format) + compliance checklist export

## 🧠 Lessons Learned
- A focused tool with fewer features can deliver a better user experience than an “all-in-one” dashboard.
- Personalisation (environment + context) significantly improves the usefulness of security guidance.
- Static guidance should be stored and reused, while AI generation should focus on user-specific analysis.


