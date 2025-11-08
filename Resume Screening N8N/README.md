# AI-Powered Resume Screening (OpenAI + n8n + Supabase)

## Summary
Automates resume–JD matching and returns match score, reasons, and summary.

## Features
- Match % (10% step), strengths, gaps, concise summary
- JSON-structured output
- Optional Supabase storage

## Tech
n8n, OpenAI (Chat Completions + JSON schema), Supabase

## Setup
1) Export `workflow.json` from n8n and import via “Import from File”.
2) Create credentials in n8n:
   - OpenAI API Key
   - (Optional) Supabase URL + Key
3) Update the **Set Variables** node:
   - `file_url` (resume PDF)
   - `job_description`
4) Run: `Execute Workflow`

## Environment
Copy `env.example` → `.env` and fill values (do not commit secrets).

## Screenshot
![Overview](./screenshots/overview.png)

## Notes / Limitations
- Long PDFs: consider truncation/chunking before LLM call.
- Do not commit API keys or tokens.
