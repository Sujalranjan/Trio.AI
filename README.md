# MemBrain — Enterprise Neural Cortex

**Tagline:** Ending Corporate Amnesia through Semantic Knowledge Graphs.

## 🚀 Setup & Installation
1. **Clone the repo:** `git clone [https://github.com/Sujalranjan/Trio.AI]`
2. **Backend Setup:**
   - `cd backend`
   - `python -m venv venv`
   - `source venv/bin/activate` (or `venv\Scripts\activate` on Windows)
   - `pip install fastapi uvicorn requests python-multipart`
3. **Run Backend:** `uvicorn main:app --reload`
4. **Frontend Setup:** Open `frontend/index.html` in a modern web browser (Google Chrome recommended for Voice features).

## 🔑 Environment Variables
- `ALPHANIMBLE_API_KEY`: Required for cloud vector indexing.
- `ALPHANIMBLE_BASE_URL`: The production endpoint for the MemBrain API.

## 👥 Team: [YOUR TEAM NAME]
- **Sujal:** Lead Full-Stack Architect & Physics Engine Developer.
- **Yashica:** UI/UX Visionary & Brand Identity.
- **Melvin:** Backend Integration & Data Strategy.

## 🧠 Project Description
**The Problem:** Large organizations suffer from "Corporate Amnesia." Critical decisions, meeting outcomes, and SOPs are lost in siloed chats or forgotten when employees leave.
**The Solution:** MemBrain acts as a centralized "External Cortex." It captures unstructured data via Voice, Files, and Text, then uses Vector Embeddings to visualize relationships in a real-time Knowledge Graph.

## 🛠 Tech Stack
- **Frontend:** HTML5, CSS3 (Glassmorphism), Vanilla JavaScript, Canvas API (Custom Force-Directed Graph).
- **Backend:** Python 3.10, FastAPI, Uvicorn.
- **AI/Database:** AlphaNimble (Vector Store & Semantic RAG), Web Speech API (On-device STT).
