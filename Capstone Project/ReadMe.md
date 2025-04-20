[![View on Kaggle](https://img.shields.io/badge/View%20on-Kaggle-blue?style=for-the-badge&logo=kaggle)](https://www.kaggle.com/code/mohammadjavadahmadi/academic-research-assistant-ara)

# 🧠 Academic Research Assistant (ARA) – Gen AI Capstone Project

> Capstone submission for the **5‑Day Gen AI Intensive Course with Google**  
> 📅 Course Dates: March 31 – April 4, 2025  
> 📝 Submission Window: April 4 – April 20, 2025

---

## 🚀 Project Overview

**ARA** is a Retrieval-Augmented, Agentic LLM system designed to answer questions about academic research papers. It combines Google’s Gemini API with LangChain tools, document embeddings, a FAISS vector index, and prompt engineering techniques to build a professional-grade educational assistant.

---

## 🧪 Demonstrated Gen AI Capabilities

This project demonstrates **nine** core capabilities:

| # | Capability                        | Demonstrated In Section |
|---|----------------------------------|--------------------------|
| 1 | Structured JSON Output           | § 3, § 5.1               |
| 2 | Few-Shot Prompting               | § 3                     |
| 3 | Embeddings                       | § 4                     |
| 4 | Vector Search / Vector Store     | § 4                     |
| 5 | Retrieval-Augmented Generation   | § 5                     |
| 6 | Agents & Function Calling        | § 5                     |
| 7 | Context Caching                  | § 10                    |
| 8 | Long Context Window              | § 8                     |
| 9 | Gen AI Evaluation (LLM-based)    | § 6, § 9                |

---

## 🔧 System Components

- **Gemini Pro/Flash Models** — for structured content generation, few-shot reasoning, and agentic response planning.
- **LangChain Tools** — for prompt templates, agent orchestration, and tool integration.
- **FAISS Index** — to power similarity-based document retrieval.
- **Sentence Transformers** — to embed paper abstracts and user queries.
- **Long Context Handling** — demonstrates Gemini 1.5 Pro's ability to reason over >10k token inputs.

---

## 🧪 Key Features

### ✅ JSON-Only Answers
ARA always returns valid JSON output to ensure machine-readability and deterministic structure for downstream applications.

### 🛠️ Agent-Based Design
ARA uses a LangChain **function-calling agent** with an embedded search tool to ground its responses in retrieved data.

### 🧠 Long Context Summarization
Demonstrates Gemini’s ability to understand and summarize inputs exceeding 15,000 tokens.

### 📈 Mini-MLOps Evaluation Loop
Performs batch LLM-based self-grading across sample queries, simulating an automated evaluation loop.

---

## 📋 Sample Use Cases

- **Educational Research Assistant**
- **Citation-Aware Paper Summarizer**
- **Multistep Reasoning with Grounded References**
- **LLM Evaluation and Benchmarking Tool**

---

## 🏁 Final Score Readiness Checklist

- ✅ Compiles end-to-end without error  
- ✅ Demonstrates 9 Gen AI capabilities  
- ✅ Structured documentation with code explanations  
- ✅ Agent, RAG, Embeddings, Long-Context, Evaluation  
- ✅ Public-ready, professional design and output  

---

## 📚 Citation

Addison Howard, Brenda Flynn, Myles O'Neill, Nate, and Polong Lin.  
**Gen AI Intensive Course Capstone 2025Q1**.  
[https://kaggle.com/competitions/gen-ai-intensive-course-capstone-2025q1](https://kaggle.com/competitions/gen-ai-intensive-course-capstone-2025q1)

---
