<div align="center">
  
# 🧠 KnowledgeFlow AI
### Enterprise Retrieval-Augmented Generation (RAG) & Semantic Vector Engine

[![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-Backend-000000?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Gemini AI](https://img.shields.io/badge/Google_Gemini-1.5_Flash-8E75B2?style=for-the-badge&logo=google&logoColor=white)](https://deepmind.google/technologies/gemini/)

*A zero-hallucination, deeply contextual Intelligence Engine designed to perfectly extract, vectorize, and synthesize enterprise knowledge.*

</div>

---

## 🌟 Introduction

**KnowledgeFlow AI** is a state-of-the-art Enterprise Retrieval-Augmented Generation (RAG) platform. Traditional RAG systems often suffer from "chunking blindness" and hallucination. KnowledgeFlow AI solves this by introducing a proprietary **Hybrid Semantic Dense Vector Engine**.

**Key Architectural Breakthroughs:**
* 🧬 **Deep DOCX Extraction:** Seamlessly parses hidden tables, rows, and cells—not just paragraphs.
* 🧮 **Absolute Phrase Locking:** Utilizes Contiguous Bi-Gram Sequence Boosting (+500.0 multiplier) to mathematically guarantee the retrieval of exact phrases (e.g., specific definitions or policy rules).
* 🪟 **Sliding Window Chunking:** Eliminates hard-cut boundaries so critical sentences are never split across vector dimensions.
* 🤖 **Context-Aware Synthesis:** Powered by **Gemini 1.5 Flash**, the engine strictly anchors its generative answers to your indexed data while "thinking beyond the document" to provide rich, educational explanations.

---

## 🔐 Secure Administrative Access

### 1. Provision Workspace (Register)
Security begins at the initialization phase. The registration node creates a secure Administrator profile using **Werkzeug PBKDF2 password hashing**. The UI features a real-time mathematical vector alignment check to ensure password confirmation matches perfectly before allowing database writes.

[Register Page] <img width="1908" height="972" alt="Screenshot 2026-03-23 182401" src="https://github.com/user-attachments/assets/959cfa66-cb31-40dd-9f4d-f512be957db7" />


### 2. Initialize Session (Login)
Enterprise-grade session management. Upon entering correct credentials, the backend authenticates against the MySQL `users` table and generates a secure Flask Session. Unauthenticated attempts to access the internal dashboard are actively intercepted and routed back to this portal.

[Login Page] <img width="1899" height="972" alt="Screenshot 2026-03-23 182421" src="https://github.com/user-attachments/assets/8120f54c-8978-414c-bf11-cef8ac9bb3a7" />


---

## 📂 Knowledge Pipeline

### 3. Multi-Format Ingestion (Dashboard)
The command center of your Knowledge Base. This dashboard provides real-time telemetry on system health (Indexed Documents, Semantic Chunks, Latency, and Token Consumption).
* **Drag-and-Drop Ingestion:** Seamlessly upload `.pdf`, `.docx`, `.txt`, `.csv`, and `.md` files.
* **Live Registry:** Instantly indexes and chunks the document, updating the active Vector Database Registry in real-time.

[Dashboard Page] <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7930d840-d0f6-44e3-b481-9240e1c43460" />


### 4. Semantic Vector Indexing
Transparency into the black box. This interface visualizes the **Deterministic Dense Gaussian Projections** applied to your data. View how your text is mathematically translated into 768-dimensional L2-normalized arrays, ensuring absolute precision during Cosine Similarity retrieval.

[Semantic Vector Indexing] <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/481a6572-e426-4041-b427-99ec231a8956" />


---

## 🧠 Intelligence Core

### 5. Context-Aware Engine (Chat Interface)
The generative front-end of the RAG system. When a query is entered:
1. The mathematical engine hashes the query and N-grams.
2. It scans millions of dimensional vectors in milliseconds.
3. It passes the highest-scoring semantic chunk to the **Gemini Intelligence Engine** for natural language synthesis.

![Context-Aware Engine] <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d19d1533-803a-4622-bb03-c88c795dcade" />


### 6. Source Attribution
Zero hallucination means absolute traceability. The Source Attribution module allows administrators to see *exactly* which document—and which exact paragraph/chunk—the LLM utilized to generate its response, alongside the mathematical Confidence Score of the retrieval.

[Source Attribution] <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d00411cb-25fa-475f-a646-6e3f3d4a2af1" />


---

## 📊 Analytics & Records

### 7. Real-Time Metrics & Persistent Chat History
KnowledgeFlow AI features a dedicated **Metrics Telemetry Engine** that calculates exact token consumption and simulated algorithm latency per query.
* **Metrics:** Monitor system efficiency, compute loads, and API handshake speeds.
* **Chat History:** Every query, AI response, exact matched quote, and confidence score is permanently logged in the MySQL `chat_logs` table for administrative review and audit compliance.

[Analytics & History] <img width="1920" height="1080" alt="Screenshot (90)" src="https://github.com/user-attachments/assets/89dd3e39-0e8a-43e7-bc7a-1781425b6689" />
<img width="1920" height="1080" alt="Screenshot (89)" src="https://github.com/user-attachments/assets/4742a986-2259-4522-9a05-0766cdd551f0" />


---

## ⚙️ Technical Architecture & Stack

| Component | Technology Used |
| :--- | :--- |
| **Frontend UI** | HTML5, CSS3 (Custom Glassmorphism & Enterprise UI), Vanilla JS |
| **Backend Core** | Python, Flask Framework |
| **Database** | MySQL (Connection Pooling, Multi-Table Relational Schema) |
| **NLP Pipeline** | Porter Stemmer, Advanced N-Gram Hash Filtering, Custom Stopwords |
| **Vector Math** | Dense Gaussian Array Projections, L2 Normalization, Cosine Similarity |
| **Generative AI** | Google Generative AI API (`gemini-1.5-flash`) |
| **Document Parsing** | `python-docx`, `PyPDF2` |

---
<div align="center">
  <i>Developed for precision. Engineered for the Enterprise.</i>
</div>
