# ClauseIQ-AI

ClauseIQ is an AI-powered contract analysis assistant that helps users understand PDF contracts by extracting the contract text and using AI to identify important information such as summaries, risks, obligations, and recommendations.

## Features

- Upload PDF contracts
- Extract text from PDF documents
- Generate an AI-powered contract summary
- Identify important risks and potential concerns
- Extract obligations, deadlines, payments, and notice periods
- Provide practical recommendations based only on the contract
- Ask follow-up questions about the uploaded contract
- Simple web-based interface

## How It Works


PDF Contract
     ↓
ClauseIQ Frontend
     ↓
FastAPI Backend
     ↓
PDF Text Extraction
     ↓
Gemini AI
     ↓
Contract Analysis
     ↓
Summary / Risks / Obligations / Recommendations

## 🤖 AI Stack & Architecture
* **LLM Engine:** Google Gemini API (`google-generativeai`)
* **Core Contribution (by @Joeljanto):** 
  * Handled the complete API orchestration, authentication, and model parameter tuning (temperature, top_p).
  * Engineered robust system instructions and custom prompt templates to handle legal context windows efficiently.
  * Designed structured JSON response structures to prevent model hallucinations during data extraction.

## 🛠️ Built With
* Python
* Google Gemini API
* 
