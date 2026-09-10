# ClauseIQ-AI

An intelligent legal tech platform built to automate document parsing and analyze legal contract clauses with high-precision AI.

## 🚀 Key Features
* **AI-Powered Clause Analysis:** Uses advanced LLM pipelines to extract and parse specific clauses from complex legal documents.
* **Structured Data Outputs:** Automatically formats raw text into clean, structured data for easy review.

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
