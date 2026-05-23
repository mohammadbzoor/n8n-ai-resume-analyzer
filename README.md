# n8n-ai-resume-analyzer

AI-powered ATS Resume Analyzer and CV Assistant built with n8n, OpenAI, and PDF processing automation.

Public documentation repository for portfolio and project overview purposes.

---

# Overview

This project is an intelligent ATS-powered Resume Analysis and CV Assistant system designed to analyze resumes, generate deterministic ATS scores, detect missing keywords, provide actionable recommendations, and assist users with AI-powered CV optimization.

The system was built using:
- n8n
- OpenAI
- PDF processing automation
- Deterministic ATS scoring logic
- Structured JSON response pipelines

---

# Features

## ATS Resume Analysis
- Deterministic ATS scoring
- ATS compatibility evaluation
- Resume strengths & weaknesses analysis
- Missing keyword detection
- Structured JSON outputs
- Resume quality assessment

## AI CV Assistant
- Resume rewriting
- Resume improvement suggestions
- ATS explanation assistant
- Resume-focused Q&A
- Section rewriting
- Professional optimization suggestions

## File Processing
- PDF upload validation
- PDF text extraction
- Resume cleaning & normalization
- CV hashing & preprocessing

---

# System Architecture

![Architecture](screenshots/architecture-overview.png)

The workflow processes uploaded resumes through multiple AI-powered stages:
1. PDF validation
2. Text extraction
3. Resume normalization
4. ATS analysis
5. AI optimization
6. Structured JSON response generation

---

# Main Workflow

![Workflow](screenshots/workflow-overview.png)

The ATS pipeline is fully automated using n8n workflows and OpenAI models.

Core workflow components:
- Webhook processing
- PDF extraction
- CV cleaning
- ATS scoring
- AI assistant handling
- Response formatting

---

# ATS Analysis Example

![ATS Analysis](screenshots/ats-analysis.png)

The system generates:
- ATS score
- ATS level
- Resume strengths
- Resume weaknesses
- Missing keywords
- Actionable recommendations

---

# AI CV Assistant

![CV Assistant](screenshots/cv-assistant.png)

The AI assistant supports:
- Resume improvement
- Resume rewriting
- ATS explanation
- Resume-focused conversations
- Structured JSON responses

---

# JSON Response Example

![JSON Response](screenshots/json-response.png)

The platform returns machine-readable structured responses for frontend integrations and automation systems.

---

# Technologies Used

## Automation
- n8n

## AI
- OpenAI GPT-4o
- OpenAI GPT-5.4-mini

## Processing
- PDF extraction
- JavaScript preprocessing
- Deterministic ATS scoring

## Infrastructure
- Webhooks
- JSON APIs
- Structured workflow pipelines

---

# Workflow Components

## Resume Processing Pipeline
- Validate Uploaded File
- Extract PDF Text
- Clean CV Text
- Generate CV Hash

## ATS Analysis Engine
- CV Analysis AI
- Deterministic Scoring
- Resume Evaluation

## AI Assistant Engine
- Resume Q&A
- Resume Rewrite
- ATS Explanation
- Resume Improvements

---

# Project Goals

This project was designed to:
- Simulate real ATS systems
- Provide deterministic resume scoring
- Improve resume quality automatically
- Build AI-powered resume automation
- Deliver structured ATS analysis
- Support intelligent resume optimization

---

# Future Improvements

Planned features:
- Multi-language resume analysis
- Job description matching
- LinkedIn integration
- Resume benchmarking
- AI cover letter generation
- Advanced ATS simulation
- Recruiter scoring models

---

# Security & Validation

Implemented protections:
- PDF-only validation
- Structured JSON enforcement
- CV-only assistant restrictions
- Deterministic scoring rules
- Hallucination prevention
- Invalid request rejection

---

# Repository Structure

```bash
screenshots/
docs/
README.md
.env.example
