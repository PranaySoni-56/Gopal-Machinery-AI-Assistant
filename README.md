# Gopal Machinery AI Assistant 🤖

*A Real-World Conversational AI Solution for a Local Business*


## 1. Project Overview

### Purpose

The **Gopal Machinery AI Assistant** is a conversational AI chatbot built to support and automate customer interactions for **Gopal Machinery**, a sewing machine sales and repair business operating since **1999** in Sadar Bazaar, Begun, Chittorgarh, Rajasthan.

### Problem Statement

The business regularly receives repetitive customer queries related to:

* Product availability
* Sewing machine repairs and servicing
* Store-related information
* Alternative product suggestions

Handling these queries manually consumes time and can lead to inconsistent responses.

### Business Context

As a traditional retail and service business, Gopal Machinery needed a **simple, reliable, and intelligent digital assistant** to improve customer experience without disrupting existing operations.

## 2. Scope and Stakeholders

### Project Scope

This project focuses on:

* Automating customer query handling
* Providing business-aligned responses
* Enforcing store-specific rules (what is sold / not sold)
* Supporting conversational context

### Stakeholders

* **Business Owner:** Gopal Machinery
* **Customers:** Walk-in and online customers seeking information
* **Developer:** Project author (AI Assistant developer)

## 3. Technology Stack

### Languages & Tools

* **Python**
* **Jupyter Notebook / Google Colab**

### AI & LLM Stack

* **LLaMA models (via Ollama)**
* Extendable to **OpenAI-compatible APIs**

### Core Concepts Used

* Prompt engineering
* Conversational memory (chat history)
* Rule-based + LLM hybrid logic
* Streaming responses

## 4. Setup and Installation

### Prerequisites

* Python 3.9+
* Jupyter Notebook or Google Colab
* Ollama installed (for local LLaMA models)

### Local Setup

1. Clone the repository
2. Install dependencies:

   pip install -r requirements.txt
   ```
3. Start Ollama server:

   ```
   ollama serve
   ```
4. Open the notebook:

   ```
   notebook/Conversational_AI_Chatbot.ipynb
   ```
5. Run all cells


## 5. How to Use

### Features

* Conversational customer interaction
* Business-rule enforcement via system prompts
* Context-aware replies using chat history
* Safe handling of unavailable items with alternatives

### Typical Workflow

1. Customer asks a question
2. System prompt applies business rules
3. Chat history provides context
4. LLM generates a business-aligned response
5. Response is streamed to the user

## 6. Architecture

### High-Level Architecture (Textual)

User Query
   ↓
System Prompt (Business Rules)
   ↓
Chat History + User Message
   ↓
LLM (LLaMA via Ollama)
   ↓
Controlled AI Response
```

### Modules

* Prompt Controller
* Chat History Manager
* LLM Interface
* Response Streamer Gradio

## 7. Deployment and Maintenance

### Deployment Options

* Local system (Ollama)
* Cloud VM (AWS EC2)
* Web app integration

### CI/CD (Future Scope)

* GitHub Actions for linting
* Automated deployment for backend services

### Maintenance

* Update system prompts as business rules change
* Periodic model upgrades
* Log customer queries for improvement

## 8. Business Impact

### Expected Benefits

* Reduced manual customer support effort
* Faster and consistent customer responses
* Improved customer satisfaction
* Digital presence for a local SME

### Measurable Outcomes (Expected)

* Lower response time
* Higher customer engagement
* Reduced repetitive queries handled manually

## 9. Contact and Credits

### Business Owner

**Gopal Machinery**

Sadar Bazaar, Begun
Chittorgarh, Rajasthan, India

### Developer

Project developed as a real-world AI solution applying data science, LLMs, and prompt engineering to a live business problem.

> This project is created with permission for educational and portfolio purposes.

### Contributions

* This is a business-specific project.
* Contributions are welcome for technical improvements, but business rules should not be modified without owner consent.

## Disclaimer

This AI assistant provides informational support only and does not replace direct business communication for pricing, final availability, or critical decisions.
