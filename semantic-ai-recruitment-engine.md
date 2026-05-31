![OpenAI](https://img.shields.io/badge/OpenAI-AI-black)
![n8n](https://img.shields.io/badge/n8n-Automation-orange)
![Pinecone](https://img.shields.io/badge/Pinecone-Vector%20Database-blue)
![Cohere](https://img.shields.io/badge/Cohere-Reranking-green)
![Vector Search](https://img.shields.io/badge/AI-Semantic%20Search-purple)

[![Back to Main Ecosystem](https://img.shields.io/badge/Back%20to-Main%20Ecosystem-purple?style=for-the-badge)](./README.md)

# Semantic AI Recruitment Engine

Semantic AI recruitment engine using Pinecone, OpenAI embeddings, Cohere reranking, and intelligent candidate matching automation.

Public documentation repository for portfolio and project overview purposes.

---

# Overview

This project is an intelligent AI-powered recruitment engine designed for semantic candidate retrieval, vector indexing, intelligent reranking, and AI-assisted hiring automation.

The platform enables recruiters and companies to:

* Search candidates semantically
* Match developers intelligently
* Retrieve candidates using vector embeddings
* Perform AI-powered recruitment filtering
* Rank candidates using reranking pipelines

The system was built using:

* n8n
* OpenAI
* Pinecone Vector Database
* Cohere Reranking
* Semantic embeddings
* Vector retrieval pipelines

---

# AI Recruitment Engine Architecture

<img width="747" height="658" alt="AI Recruitment Engine Architecture" src="https://github.com/user-attachments/assets/561c309c-995e-479f-a118-3f8581fd0650" />

This architecture represents the recruiter-side AI recruitment engine responsible for candidate preprocessing, vector indexing, semantic retrieval, intelligent reranking, and AI-powered hiring automation.

Core capabilities include:

* Candidate vector indexing
* Pinecone vector storage
* OpenAI embeddings
* Semantic candidate search
* Cohere reranking
* Intelligent recruitment assistance
* AI-powered candidate matching

---

# Recruitment Workflow

```text
Recruiter Request
        ↓
Candidate Preprocessing
        ↓
Vector Embeddings Generation
        ↓
Pinecone Vector Storage
        ↓
Semantic Candidate Retrieval
        ↓
Cohere Reranking
        ↓
AI Recruitment Assistant
        ↓
Structured JSON Response
```

---

# Features

## Semantic Candidate Search

* Natural language candidate search
* Context-aware candidate retrieval
* Skill and experience matching
* Candidate profile understanding
* Search based on meaning instead of exact keywords

## Vector Indexing

* Candidate profile preprocessing
* Developer skills normalization
* Projects and experience processing
* OpenAI embeddings generation
* Pinecone vector storage

## AI Reranking

* Cohere reranking pipeline
* Relevance-based candidate ranking
* Improved search result quality
* Better matching between recruiter intent and candidate profiles

## Recruitment Assistant

* AI-assisted candidate recommendations
* Structured candidate matching
* Query understanding
* Recruitment-focused response formatting

---

# Technologies Used

## Automation

* n8n

## AI and Search

* OpenAI Embeddings
* OpenAI Chat Models
* Pinecone Vector Database
* Cohere Reranking
* Semantic Search

## Processing

* Candidate preprocessing
* Text normalization
* Vector embeddings generation
* Candidate ranking
* JSON response formatting

## Infrastructure

* Webhooks
* JSON APIs
* Structured workflow pipelines

---

# Candidate Indexing Flow

```text
Candidate Profile Created / Updated
        ↓
Collect Candidate Skills, Projects, Experiences
        ↓
Normalize Candidate Text
        ↓
Generate OpenAI Embeddings
        ↓
Store Candidate Vectors in Pinecone
```

---

# Semantic Search Flow

```text
Company Search Query
        ↓
Normalize Recruiter Request
        ↓
Generate Query Embeddings
        ↓
Search Candidate Vector Database
        ↓
Retrieve Relevant Candidates
        ↓
Rerank Results with Cohere
        ↓
Return Structured Candidate Matches
```

---

# Example Recruiter Query

```text
Need a React developer with experience in AI automation, dashboards, and API integration
```

The system understands the meaning behind the query and retrieves candidates based on technical context, not only exact keyword matching.

---

# Example JSON Output

```json
{
  "success": true,
  "query": "Need a React developer with experience in AI automation and dashboards",
  "matches": [
    {
      "candidateId": 21,
      "name": "Candidate Name",
      "matchScore": 0.91,
      "matchedSkills": [
        "React.js",
        "API Integration",
        "AI Automation"
      ],
      "reason": "Candidate has strong React experience, dashboard projects, and AI workflow integration exposure."
    }
  ]
}
```

---

# My Contribution

My contribution in this part focused on designing and supporting the recruiter-side AI workflow logic that helps companies find relevant candidates using semantic search and structured matching.

| Area                    | Contribution                                                             |
| ----------------------- | ------------------------------------------------------------------------ |
| n8n Workflow Logic      | Designed and supported recruiter-side automation workflows               |
| Candidate Preprocessing | Supported preparation of candidate skills, projects, and experience data |
| OpenAI Embeddings       | Supported embedding-based candidate indexing and search                  |
| Pinecone Integration    | Worked with vector search concepts for candidate retrieval               |
| Cohere Reranking        | Supported relevance-based reranking logic                                |
| Recruitment Assistant   | Helped structure natural language recruitment matching logic             |
| JSON Responses          | Helped return structured candidate match results to the platform         |

---

# Related Documentation

* [Back to Main Ecosystem](./README.md)
* [View Frontend Documentation](./frontend-development.md)
