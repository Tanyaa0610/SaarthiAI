# SaarthiAI

**Autonomous Multi-Agent Banking Assistant for Intelligent Customer Acquisition**

> An Agentic AI solution developed for the **SBI Hackathon – Global FinTech Fest (GFF) 2026**

---

## Overview

SaarthiAI is a concept-stage multi-agent AI platform designed to simplify customer acquisition for State Bank of India (SBI). The project explores how specialized AI agents can collaborate to assist customers throughout the onboarding journey—from understanding their requirements to completing account opening and post-onboarding engagement.

Instead of relying on a single chatbot, SaarthiAI distributes responsibilities across multiple AI agents, allowing each agent to perform a focused task while working together through a central orchestrator.

This repository documents the proposed architecture, solution design, and initial development plan prepared as part of the idea submission stage for the SBI Hackathon.

---

## Problem Statement

Although digital banking has significantly improved customer accessibility, many users still abandon the onboarding process before successfully opening an account.

Some of the common challenges include:

* Complex onboarding workflows
* Lack of personalized product recommendations
* Multiple verification steps
* Manual document validation
* Limited assistance after an application is left incomplete

Traditional banking chatbots primarily answer customer queries but rarely assist in completing the end-to-end onboarding process.

---

## Proposed Solution

SaarthiAI introduces an Agentic AI architecture where multiple AI agents collaborate to support customers throughout their onboarding journey.

Each agent is responsible for a specific task, while a central Agent Orchestrator manages workflow execution and shares customer context between agents.

### Specialized AI Agents

* Intent Detection Agent
* Customer Profiling Agent
* Product Recommendation Agent
* Eligibility Verification Agent
* Document Processing Agent
* Fraud Detection Agent
* KYC Agent
* Follow-up Agent

---

## High-Level Workflow

```text
Customer
      │
      ▼
SBI Digital Channels
(YONO • Website • WhatsApp Banking • Branch Kiosk)
      │
      ▼
Agent Orchestrator
      │
      ▼
Intent Detection
      │
      ▼
Customer Profiling
      │
      ▼
Product Recommendation
      │
      ▼
Eligibility Verification
      │
      ▼
Document Processing
      │
      ▼
Fraud Detection
      │
      ▼
KYC Verification
      │
      ▼
Follow-up & Engagement
      │
      ▼
Successful Customer Onboarding
```

---

## Key Features

* Multi-Agent AI Architecture
* Goal-Oriented Customer Assistance
* Personalized Product Recommendation
* OCR-based Document Processing
* Eligibility Verification
* Fraud Risk Assessment
* Automated Follow-up for Incomplete Applications
* Omnichannel Banking Experience
* Modular and Scalable Design

---

## Technology Stack

| Layer           | Technology                            |
| --------------- | ------------------------------------- |
| Frontend        | React.js (Planned)                    |
| Backend         | FastAPI                               |
| AI Framework    | LangGraph                             |
| Language Model  | GPT-4.1 / Llama 3                     |
| OCR             | PaddleOCR                             |
| Database        | PostgreSQL                            |
| Vector Database | FAISS                                 |
| APIs            | SBI Sandbox, DigiLocker, Aadhaar eKYC |
| Deployment      | Docker                                |

---

## Repository Structure

```text
SaarthiAI/
│
├── docs/
│   ├── ProblemStatement.md
│   ├── SolutionOverview.md
│   ├── Architecture.md
│   ├── Architecture.png
│   ├── ProcessFlow.png
│   └── SaarthiAI_Presentation.pdf
│
├── README.md
```

---

## Current Status

This repository represents the **Idea Submission / MVP Planning** phase.

At this stage, the project includes:

* Solution documentation
* System architecture
* Multi-agent design
* Backend project structure
* API planning
* Sample data

The implementation of the complete multi-agent workflow will be carried out during subsequent hackathon development stages.

---

## Future Scope

The proposed architecture can be extended to support:

* Loan onboarding
* Credit card applications
* Government scheme recommendations
* MSME banking
* Voice banking
* Regional language support
* AI-powered financial guidance

---

## Author

**Tanya**

B.Tech Computer Science Engineering

Individual Participant

SBI Hackathon – Global FinTech Fest (GFF) 2026

---

## License

This project is licensed under the MIT License.
