# 🌐 Multilingual AI Virtual Assistant for the PGRKAM Portal  
**Capstone Project | 2025**

This project presents a **Retrieval-Augmented Multilingual Conversational Assistant** designed to simplify access to job and skill development opportunities on the **Punjab Ghar Ghar Rozgar (PGRKAM)** Portal.  
Users can interact in **Punjabi, Hindi, or English**, using **text or voice**, and receive relevant guidance.

## 🎯 Problem Statement

Job seekers visiting government employment portals often face challenges such as:

|    Challenge           |                  Impact                  |
|
| Complex navigation     | Difficulty locating relevant services    |
| Language barriers      | Exclusion of Punjabi/Hindi-only speakers |
| Low digital literacy   | Reduced access to opportunities          |
| job/training data      | Increased time & confusion               |

## 🧠 Solution Overview

This assistant acts as a **virtual guide** that:
- Accepts **voice and text inputs**
- Understands **Punjabi / Hindi / English**
- Provides **context-aware answers**
- Recommends **jobs & training** based on user profile
- Uses **Retrieval-Augmented Generation (RAG)** to avoid hallucination

## 🏛️ System Architecture (Block Diagram)
User Query (Voice/Text)
↓
Language + Intent Detection
↓
Recommendation & Routing Engine
↓
RAG Module (Documents / Knowledge Base)
↓
Groq LLaMA Model (Answer Generation)
↓
Response (Text / Voice)


## 🔥 Key Features

|          Feature           |                 Description                 |

| Multilingual Support       | Punjabi, Hindi, English automatic detection |
| Voice Input & Voice Output | Speak to ask & listen to responses          |
| Job Recommendation Engine  | Suggests jobs matching user profile         |
| RAG Knowledge Retrieval    | Answers based on uploaded PDFs/data         |
| User Login System          | Saves preferences and chat history          |
| Intent-Based Navigation    | Opens correct PGRKAM portal pages           |

## 🗂 Project Structure
pgrkam-copilot/
│ app.py → Main Streamlit application
│ users.json → Local credential storage
│ data/ → Job listings / documents
│ services/
│ ├ db.py → SQLite DB helper
│ ├ llm.py → Groq API chat model
│ ├ rag.py → Vector search & retrieval
│ ├ voice.py → Speech-to-Text & TTS
│ ├ recommender.py → Job recommendation logic
│ └ utils.py → Session helpers


---

## ⚙️ Technologies Used

|          Category          |         Tools / Frameworks      |

| Frontend UI                | Streamlit                       |
| Backend Processing         | Python                          |
| Language Model | LLaMA 3.3 70B (via Groq API)                |
| Embeddings / Vector Search | FAISS or in-memory vector store |
| Text-to-Speech             | gTTS                            |
| Speech Recognition         | Google SpeechRecognition API    |
| Database                   | SQLite                          |
| Version Control            | Git & GitHub                    |



