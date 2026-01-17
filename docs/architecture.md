# Architecture (High Level)

Caledonian Shield is an AI-powered security & compliance companion built using AWS PartyRock + Bedrock + Whiskers.

## Components
- **UI:** PartyRock App (web interface)
- **LLM:** AWS Bedrock (foundation model)
- **Agent Layer:** Whiskers (prompt + workflow orchestration)
- **Outputs:** Security guidance, phishing analysis, log explanation, UK compliance mapping

## Data Safety
- No secrets stored in repo
- No real logs / credentials included
- Demo uses sanitized examples only
