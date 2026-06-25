# System Architecture

## Overview

SaarthiAI follows a modular multi-agent architecture in which specialized AI agents collaborate under the supervision of a central Agent Orchestrator. Each agent performs an independent responsibility while sharing customer context throughout the onboarding journey.

This modular approach improves maintainability, scalability, and decision quality compared to a single conversational chatbot.

---

## Architecture Layers

### 1. Customer Interaction Layer

Customers access SaarthiAI through existing SBI digital channels.

Supported channels include:

* SBI YONO
* SBI Website
* WhatsApp Banking
* Branch Digital Kiosk

---

### 2. Agent Orchestration Layer

The Agent Orchestrator manages communication between individual AI agents.

Its responsibilities include:

* Routing customer requests
* Maintaining shared customer context
* Coordinating task execution
* Managing workflow progression

---

### 3. Specialized AI Agents

The platform consists of dedicated AI agents responsible for different onboarding tasks.

* Intent Detection Agent
* Customer Profiling Agent
* Product Recommendation Agent
* Eligibility Verification Agent
* Document Processing Agent
* Fraud Detection Agent
* KYC Agent
* Follow-up Agent

Each agent performs a specific responsibility while exchanging information through the orchestrator.

---

### 4. Knowledge Layer

Agents access a common knowledge layer containing:

* SBI product catalogue
* Business rules
* Eligibility policies
* Frequently used onboarding information
* Vector knowledge base for retrieval

---

### 5. Integration Layer

The platform communicates with existing banking systems through secure APIs.

Planned integrations include:

* SBI Sandbox APIs
* Aadhaar eKYC
* DigiLocker
* Core Banking APIs
* Notification Services

---

## Design Principles

The architecture has been designed with the following principles:

* Modular AI agents
* Clear separation of responsibilities
* Scalable workflow orchestration
* API-first integration
* Human-in-the-loop support when required
* Extensible architecture for future banking services

---

## Future Enhancements

The same architecture can be extended to support:

* Loan onboarding
* Insurance products
* Government welfare schemes
* MSME banking
* Voice banking
* Regional language support
