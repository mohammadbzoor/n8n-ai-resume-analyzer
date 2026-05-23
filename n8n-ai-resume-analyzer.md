![OpenAI](https://img.shields.io/badge/OpenAI-AI-black)
![n8n](https://img.shields.io/badge/n8n-Automation-orange)
![ATS](https://img.shields.io/badge/ATS-Resume%20Analysis-blue)
![PDF](https://img.shields.io/badge/PDF-Processing-red)
![JSON](https://img.shields.io/badge/API-JSON-green)

[![Back to Main Ecosystem](https://img.shields.io/badge/Back%20to-Main%20Ecosystem-purple?style=for-the-badge)](./README.md)

# n8n-ai-resume-analyzer

AI-powered ATS Resume Analyzer and CV Assistant built with n8n, OpenAI, and PDF processing automation.

Public documentation repository for portfolio and project overview purposes.

---

# Overview

This project is an intelligent ATS-powered Resume Analysis and CV Assistant system designed to analyze resumes, generate deterministic ATS scores, detect missing keywords, provide actionable recommendations, and assist users with AI-powered CV optimization.

Core capabilities include:
- ATS resume analysis
- Resume optimization
- AI-powered CV assistance
- Deterministic ATS scoring
- Structured JSON responses
- Resume preprocessing pipelines

---

# ATS Resume Analysis Architecture

<img width="1390" height="431" alt="ATS Resume Analysis Architecture" src="https://github.com/user-attachments/assets/a93113da-f002-490e-ae8d-eedee18a17c0" />

This architecture represents the candidate-side AI ecosystem responsible for resume upload processing, PDF extraction, ATS scoring, resume optimization, structured AI evaluation, and intelligent CV assistance workflows.

---

# How It Works

```text
User Uploads Resume
        ↓
Webhook Receives Request
        ↓
PDF File Validation
        ↓
Resume Text Extraction
        ↓
CV Cleaning and Normalization
        ↓
ATS Analysis AI
        ↓
AI Resume Assistant
        ↓
Structured JSON Response
