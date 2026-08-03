# ⚖️ LawBot: Bangladesh Legal RAG System

**LawBot** is an intelligent Retrieval-Augmented Generation (RAG) system engineered to answer legal queries based on Bangladeshi Acts and Laws. Powered by **LangChain**, **FAISS**, **HuggingFace Embeddings**, and **Google Gemini 2.5 Flash**, it provides accurate, context-driven legal information while maintaining strict guardrails against misuse.

---

## 🌟 Key Features

- **🚀 Smart FAISS Vector DB**: Automatic persistence and instant loading logic to prevent re-indexing datasets across runs.
- **⚡ Advanced Embeddings**: Powered by `sentence-transformers/all-MiniLM-L6-v2` with dynamic GPU/CPU acceleration.
- **🤖 Gemini 2.5 Flash LLM**: High-speed, high-accuracy inference tuned specifically for legal assistance.
- **🛡️ Legal Safety & Ethics Guardrails**: Strict system instruction enforcing legal neutrality, refusing assistance with crime evasion, and focusing strictly on education/information.
- **📊 Robustness & Evaluation Module**: Includes noise handling tests (typos, distractor texts) and Retriever-only evaluation metrics (Hit Rate@K).

---

## 🛠️ Tech Stack & Architecture

- **Language:** Python 3.10+
- **LLM:** Google Gemini 2.5 Flash (`langchain-google-genai`)
- **Embeddings:** `sentence-transformers/all-MiniLM-L6-v2` (`langchain-huggingface`)
- **Vector Database:** FAISS (Facebook AI Similarity Search)
- **Framework:** LangChain Architecture

---

## 📁 Dataset Format

The project expects a CSV dataset (`bangladesh_legal_acts_sections.csv`) structured with the following columns:
- `act_title`: Name of the legal Act/Constitution.
- `section_no`: Relevant Section or Article number.
- `section_content`: Full text description of the section.
- `source_url`: Reference link (optional).

---

## 🚀 Getting Started

### Prerequisites

Clone the repository and install required Python packages:

```bash
git clone [https://github.com/YOUR_USERNAME/LawBot-Bangladesh-RAG.git](https://github.com/YOUR_USERNAME/LawBot-Bangladesh-RAG.git)
cd LawBot-Bangladesh-RAG
pip install -r requirements.txt


---

## 👥 Contributors / Authors

This project was developed as a collaborative effort by:

* **[Jamiur Rahman]
* **[Md. Ahmed Alif]
* **[Mahbubur Rahman Talha]

> *Special thanks to everyone who contributed to building and testing LawBot.*
