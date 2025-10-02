# Copilot Guardrails (Prompt Injection, PII Redaction, Allowlisted Tools)

Minimal example that wraps an LLM assistant with:
- Prompt injection detection
- PII redaction (emails, phone numbers)
- Tool/action allowlisting with argument validation

Run:
  python guardrails.py

(Optional) Set OPENAI_API_KEY to actually call an LLM; otherwise a mock is used.
