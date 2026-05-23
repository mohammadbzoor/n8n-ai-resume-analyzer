![OpenAI](https://img.shields.io/badge/OpenAI-AI-black)
![n8n](https://img.shields.io/badge/n8n-Automation-orange)
![ATS](https://img.shields.io/badge/ATS-Resume%20Analysis-blue)
![PDF](https://img.shields.io/badge/PDF-Processing-red)
![JSON](https://img.shields.io/badge/API-JSON-green)

[![Back to Main Ecosystem](https://img.shields.io/badge/Back%20to-Main%20Ecosystem-purple?style=for-the-badge)](./README.md)

#ATS Resume Analysis Architecture

<img width="1390" height="431" alt="ATS Resume Analysis Architecture" src="https://github.com/user-attachments/assets/a93113da-f002-490e-ae8d-eedee18a17c0" />

This architecture represents the candidate-side AI ecosystem responsible for resume upload processing, PDF extraction, ATS scoring, resume optimization, structured AI evaluation, and intelligent CV assistance workflows.

---

# Features

## ATS Analysis

- Deterministic ATS scoring
- ATS compatibility evaluation
- Resume strengths and weaknesses analysis
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

## Resume Processing

- PDF upload validation
- PDF text extraction
- Resume cleaning and normalization
- CV hashing and preprocessing

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

# ATS Analysis Example

<img width="763" height="681" alt="ATS Analysis Example" src="https://github.com/user-attachments/assets/c572895b-a1d3-477d-ad31-5c64ed88a9ed" />

The ATS engine generates:
- ATS score
- ATS level
- Resume strengths
- Resume weaknesses
- Missing keywords
- Actionable recommendations

---

# Example JSON Output

```json
{
  "success": true,
  "userId": 139,
  "chatId": 35,
  "cvId": 35,
  "atsScore": 78,
  "atsLevel": "Good",
  "status": "Good",
  "summary": "Backend Software Developer with 2 years of experience in building scalable server-side systems and integrating AI solutions.",
  "strengths": [
    "Strong technical skills in multiple programming languages and frameworks",
    "Experience with AI integration and scalable system development",
    "Active involvement in technical content creation and leadership roles"
  ],
  "weaknesses": [
    "Lack of measurable achievements in professional experience",
    "Projects lack specific outcomes or metrics",
    "Formatting could be improved for better readability"
  ],
  "recommendations": [
    "Add measurable achievements to the professional experience section, such as performance improvements, efficiency gains, or completed project impact.",
    "Include specific outcomes for projects to demonstrate business or technical value.",
    "Improve formatting consistency by using clear section headings, aligned dates, and concise bullet points."
  ],
  "isAnalyzed": true
}
