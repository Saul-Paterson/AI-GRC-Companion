# Threat Model (High Level)

## Goal
Caledonian Shield is designed as an educational security & compliance assistant to help users analyse suspicious content, understand logs, and improve security posture.

## Key Risks
- Prompt injection / malicious user input
- Sensitive data exposure (PII, credentials, internal logs)
- Over-reliance on AI output (false positives/negatives)
- Misuse of guidance for offensive purposes

## Mitigations
- Strong safety notice: do not paste credentials, tokens, or personal data
- Sanitised demo inputs only
- Clear disclaimers: educational use, not production SOC tooling
- Encourage use of official security tools for real incidents

## Data Handling
- No secrets stored in this repo
- No real customer/organisation logs included
- All examples are anonymised
