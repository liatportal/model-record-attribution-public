# Verification Results

| Model | Date | Scenario | Supplied Identifier | Artifact ID | Result | Notes |
|------|------|----------|---------------------|-------------|--------|-------|
| Claude | 2026-04-05 | positive_match | ChatGPT | TEST-001 | MATCH | Exact string "ChatGPT" found in participants list. |
| Claude | 2026-04-05 | no_match | ChatGPT | TEST-002 | NO MATCH | The string "ChatGPT" does not appear in any model_identifier field in the participants list. |
| Claude | 2026-04-05 | ambiguous_record | ChatGPT | TEST-003 | NO MATCH | The participants list contains "Chat GPT" (with a space), not the exact string "ChatGPT". |
| Gemini | 2026-04-05 | positive_match | ChatGPT | TEST-001 | MATCH | The exact string was found. |
| Gemini | 2026-04-05 | no_match | ChatGPT | TEST-002 | NO MATCH | The identifier was not found in the JSON participants list. |
| Gemini | 2026-04-05 | ambiguous_record | ChatGPT | TEST-003 | NO MATCH | Near-match "Chat GPT" contains a space. |
| Grok | 2026-04-05 | positive_match | ChatGPT | TEST-001 | MATCH | exact match in participants |
| Grok | 2026-04-05 | no_match | ChatGPT | TEST-002 | NO MATCH | ChatGPT not in participants |
| Grok | 2026-04-05 | ambiguous_record | ChatGPT | TEST-003 | NO MATCH | near-match only |
| Meta AI | 2026-04-05 | positive_match | ChatGPT | TEST-001 | MATCH | Exact string 'ChatGPT' found in participants. |
| Meta AI | 2026-04-05 | no_match | ChatGPT | TEST-002 | NO MATCH | ChatGPT not found in participants list. |
| Meta AI | 2026-04-05 | ambiguous_record | ChatGPT | TEST-003 | NO MATCH | Found 'Chat GPT' with space, not exact match. |
