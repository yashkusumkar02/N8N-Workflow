# 🚀 n8n Automation Workflows by Suyash Kusumkar

A curated collection of **production-ready n8n automation workflows**, designed for real business problems — including AI-driven automation, data processing, resume evaluation, and integrations with OpenAI, Supabase, and third-party APIs.

> Each workflow includes:  
> ✅ `workflow.json`  
> ✅ Documentation / setup guide  
> ✅ Screenshots / triggers explained  
> ✅ Optional `.env.example` (no secrets)

---

## 📂 Repository Structure

```bash
n8n-workflows/
├─ README.md                     # You're here
├─ workflows/                    # All workflows live here
│   ├─ resume-screening/         # Example workflow
│   │   ├─ workflow.json
│   │   ├─ README.md
│   │   ├─ env.example
│   │   ├─ screenshots/
│   │   └─ notes.md
├─ assets/                       # Shared images / demo gifs
└─ .gitignore
```

---

## 📌 Workflow Index

| Workflow Name | Description | Tech Used | Link |
|--------------|-------------|-----------|------|
| Resume Screening (AI-Driven) | Automatically evaluates resumes vs job descriptions and provides match %, strengths, gaps, summary. | n8n · OpenAI · Supabase | [Explore]([./workflows/resume-screening/README.md](https://github.com/yashkusumkar02/N8N-Workflow/tree/main/Resume%20Screening%20N8N)) |
| *(More coming soon...)* | — | — | — |

---

## 🛠️ How to Use Any Workflow

### ✅ Import into n8n

1. Open **n8n** (self-hosted / cloud)
2. Go to: `Workflows → Import → From File`
3. Select the respective `workflow.json`
4. Update credentials (`OpenAI`, `Supabase`, etc.)

> No credentials are included in this repo — use `.env.example` as a reference.

---

## 📄 Standards & Best Practices

All workflows follow:

- Modular folder structure
- Simplicity over complexity
- Production-ready JSON schema responses (for LLM workflows)
- Clean naming of nodes and consistent flow layout
- No hardcoded credentials (only placeholders)

---

## 🌟 Why This Repository Exists

I use n8n to automate:
- Repetitive product & engineering workflows  
- AI document processing (resume screening, extraction, analysis)
- Business automations & integrations

Rather than keeping these internally, I’m open-sourcing them so others can:
✅ Learn  
✅ Fork  
✅ Improve  
✅ Use directly in production

---

## 🤝 Contributing

Contributions are welcome.

👉 You can:
- Submit a PR
- Suggest workflows via Issues
- Request automation ideas

---

## ❓ Issues / Support

If you face any problem with:
- Environment setup
- Missing nodes
- Workflow execution

---

## 🛡 License

MIT License — use freely for personal or commercial projects.

---

### ⭐ If this repo helps you, consider giving it a star → it motivates me to share more workflows.

