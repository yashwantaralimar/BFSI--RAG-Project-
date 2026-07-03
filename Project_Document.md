# BFSI RAG Project — Complete Project Document

**Project Name:** Bank Policy Q&A Chatbot using RAG
**Domain:** BFSI (Banking, Financial Services & Insurance)
**Technology:** RAG (Retrieval Augmented Generation)
**Tech Stack:** Python | LangChain | FAISS | HuggingFace | PyPDFLoader
**Date:** July 2026

---

## 1. Problem Statement

Bank customers and employees frequently need to look up policy details such as loan eligibility, credit card limits, KYC requirements, and FD interest rates. Searching through lengthy PDF documents manually is time-consuming and error-prone. There is a need for an intelligent system that can instantly answer natural language questions based on actual bank policy documents.

---

## 2. Objective

To build a RAG-based (Retrieval Augmented Generation) Q&A chatbot that:
- Ingests BFSI domain documents (bank policies, loan terms, insurance guidelines)
- Converts them into searchable vector embeddings using FAISS
- Answers natural language questions by retrieving only the most relevant sections
- Provides accurate, document-grounded answers without hallucination

---

## 3. RAG Architecture

```
INPUT: Bank Policy Document (Text/PDF)
              ↓
    [PyPDFLoader / Text Loader]
              ↓
    [RecursiveCharacterTextSplitter]
       Splits into 500-char chunks
              ↓
    [HuggingFace Embeddings]
       all-MiniLM-L6-v2 model
       Converts text → vectors
              ↓
    [FAISS Vector Store]
       Stores & indexes vectors
              ↓
    USER ASKS A QUESTION
              ↓
    [FAISS Similarity Search]
       Finds top 3 relevant chunks
              ↓
    OUTPUT: Relevant policy answer
```

---

## 4. Tech Stack Details

| Tool | Version | Purpose |
|---|---|---|
| Python | 3.9.12 | Core programming language |
| LangChain | 0.1.20 | RAG pipeline orchestration |
| LangChain-Community | 0.0.38 | Document loaders, vector stores |
| FAISS-CPU | 1.7.4 | Vector similarity search |
| PyPDF | 4.2.0 | PDF document loading |
| Sentence-Transformers | 2.7.0 | Text embedding generation |
| HuggingFace Hub | 0.34.3 | Pre-trained embedding models |

---

## 5. Why RAG for BFSI?

| Challenge | RAG Solution |
|---|---|
| LLMs hallucinate policy details | RAG grounds answers in real documents |
| Policies change frequently | Just update the document, no retraining needed |
| Need precise financial figures | Retrieved directly from source document |
| Compliance requirement | Every answer is traceable to source document |
| No internet/API dependency | Runs fully offline with HuggingFace local models |

---

## 6. BFSI Topics Covered

1. **Home Loan Policy** — Eligibility, interest rates, tenure, processing fees
2. **Personal Loan Policy** — Amount limits, repayment, foreclosure
3. **Credit Card Policy** — Credit score requirements, limits, charges
4. **Savings Account Policy** — Minimum balance, ATM limits, UPI limits
5. **Life Insurance Policy** — Sum assured, premium modes, tax benefits
6. **KYC Guidelines** — Required documents, update frequency, video KYC
7. **Fixed Deposit Policy** — Interest rates, senior citizen benefits, premature withdrawal

---

## 7. Project Flow — Step by Step

| Step | Action | Expected Output |
|---|---|---|
| 1 | Install libraries | ✅ All libraries installed |
| 2 | Import modules | ✅ All imports successful |
| 3 | Create BFSI document | ✅ bfsi_policy.txt created |
| 4 | Load & split into chunks | ✅ N chunks created |
| 5 | Create embeddings + FAISS | ✅ Vector store created |
| 6 | Build RAG Q&A function | ✅ Function ready |
| 7 | Run 5 test cases | ✅ All 5 pass |
| 8 | Print summary report | ✅ 100% pass rate |

---

## 8. Key Features

- **Zero API Key Required** — Uses local HuggingFace models
- **Fully Offline Capable** — After first model download
- **BFSI Specific** — Document tailored to banking domain
- **Traceable Answers** — Every answer shows which document section was used
- **Scalable** — Can add more PDFs to the vector store easily
- **Fast Retrieval** — FAISS provides millisecond-level similarity search

---

## 9. e2 GenAI Competency Mapping

| Competency | Evidence |
|---|---|
| GenAI Concepts | Implemented RAG architecture end-to-end |
| Prompt Engineering | Structured retrieval queries for BFSI domain |
| Vector Databases | Created and queried FAISS vector store |
| Embeddings | Used sentence-transformers for text vectorization |
| Document Processing | Loaded, chunked, and indexed policy documents |
| Domain Application | Applied GenAI to real BFSI use case |

---

## 10. Future Enhancements

- Add PDF upload support for real bank documents
- Integrate Llama3.2 via Ollama for richer generated answers
- Add chat history for multi-turn conversations
- Build a Streamlit web UI for the chatbot
- Add multiple document support (insurance + banking together)

---

*BFSI RAG Project | TCS GenAI Lab | July 2026*
