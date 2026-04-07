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
| Perplexity | 2026-04-06 | valid_positive_match | ChatGPT | TEST-001 | MATCH | Exact identifier found in participants |
| Perplexity | 2026-04-06 | valid_no_match | ChatGPT | TEST-002 | NO MATCH | No exact ChatGPT identifier present |
| Perplexity | 2026-04-06 | invalid_malformed_record | ChatGPT | TEST-003 | NOT EVALUATED | Invalid record structure |
| ChatGPT | 2026-04-06 | valid_positive_match | ChatGPT | TEST-001 | MATCH | Valid record with exact match |
| ChatGPT | 2026-04-06 | valid_no_match | ChatGPT | TEST-002 | NO MATCH | Valid record without exact match |
| ChatGPT | 2026-04-06 | invalid_malformed_record | ChatGPT | TEST-003 | NOT EVALUATED | Invalid record structure |
| DeepSeek | 2026-04-06 | valid_positive_match | ChatGPT | TEST-001 | MATCH | Valid record with exact match |
| DeepSeek | 2026-04-06 | valid_no_match | ChatGPT | TEST-002 | NO MATCH | Valid record without exact match |
| DeepSeek | 2026-04-06 | invalid_malformed_record | ChatGPT | TEST-003 | NOT EVALUATED | Invalid record structure |
| Mistral | 2026-04-06 | valid_positive_match | ChatGPT | TEST-001 | MATCH | Valid record with exact match |
| Mistral | 2026-04-06 | valid_no_match | ChatGPT | TEST-002 | NO MATCH | Valid record without exact match |
| Mistral | 2026-04-06 | invalid_malformed_record | ChatGPT | TEST-003 | NOT EVALUATED | Invalid record structure |
