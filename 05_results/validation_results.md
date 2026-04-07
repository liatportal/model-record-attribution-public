# Validation Results

| Model | Date | Scenario | Supplied Identifier | Artifact ID | Result | Notes |
|------|------|----------|---------------------|-------------|--------|-------|
| Claude | 2026-04-06 | valid_positive_match | ChatGPT | TEST-001 | MATCH | Exact match confirmed; all required fields present |
| Claude | 2026-04-06 | valid_no_match | ChatGPT | TEST-002 | NO MATCH | "ChatGPT" absent from participants list |
| Claude | 2026-04-06 | invalid_malformed_record | ChatGPT | TEST-003 | NOT EVALUATED | Invalid record structure |
| Gemini | 2026-04-06 | valid_positive_match | ChatGPT | TEST-001 | MATCH | Record contains required fields and the exact identifier string. |
| Gemini | 2026-04-06 | valid_no_match | ChatGPT | TEST-002 | NO MATCH | Participant list contains other models but lacks the target identifier. |
| Gemini | 2026-04-06 | invalid_malformed_record | ChatGPT | TEST-003 | NOT EVALUATED | Invalid record structure |
| Grok | 2026-04-06 | valid_positive_match | ChatGPT | TEST-001 | MATCH | positive identifier confirmed |
| Grok | 2026-04-06 | valid_no_match | ChatGPT | TEST-002 | NO MATCH | ChatGPT absent from list |
| Grok | 2026-04-06 | invalid_malformed_record | ChatGPT | TEST-003 | NOT EVALUATED | Invalid record structure |
| Meta AI | 2026-04-06 | valid_positive_match | ChatGPT | TEST-001 | MATCH | All fields valid; identifier found |
| Meta AI | 2026-04-06 | valid_no_match | ChatGPT | TEST-002 | NO MATCH | All fields present; ChatGPT absent |
| Meta AI | 2026-04-06 | invalid_malformed_record | ChatGPT | TEST-003 | NOT EVALUATED | Invalid record structure |
