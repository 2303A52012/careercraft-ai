# CareerCraft AI

**An AI-powered full-stack job application assistant** that helps users tailor resumes, generate cover letters, and streamline their job application workflow — powered by Groq's LLaMA 3.3 70B.


---

## 📦 Repositories

This project is split across two repositories for independent deployment and scalability:

| Component | Description | Repo |
|---|---|---|
| 🎨 **Frontend** | React-based UI for resume upload, job input, and AI-generated content display | [careercraft-ai-frontend](https://github.com/YOUR_USERNAME/careercraft-ai-frontend) |
| ⚙️ **Backend** | FastAPI service handling resume parsing, prompt orchestration, and Groq API integration | [careercraft-ai-backend](https://github.com/YOUR_USERNAME/careercraft-ai-backend) |

---

## 🛠️ Tech Stack

- **Frontend:** React, JavaScript
- **Backend:** FastAPI, Python
- **AI:** Groq API (LLaMA 3.3 70B)
- **Document Parsing:** PyPDF2, python-docx

## ✨ Key Features

- AI-generated, context-aware resume and cover letter content
- Resume parsing pipeline supporting PDF and DOCX uploads
- Modular REST API architecture (parsing → generation → presentation)
- Planned: live LinkedIn and GitHub data integration for richer profile-based tailoring

## 🏗️ Architecture

```
┌─────────────┐         ┌──────────────┐         ┌─────────────┐
│   Frontend  │  ───►   │   Backend    │  ───►   │   Groq API  │
│   (React)   │  ◄───   │  (FastAPI)   │  ◄───   │ (LLaMA 3.3) │
└─────────────┘         └──────────────┘         └─────────────┘
                              │
                              ▼
                      ┌───────────────┐
                      │ Resume Parser │
                      │ (PyPDF2/docx) │
                      └───────────────┘
```

---

## 👤 Author

**Palakurthi Lalith Prakash**
[GitHub](https://github.com/YOUR_USERNAME) · [LinkedIn](https://linkedin.com/in/YOUR_LINKEDIN)
