# 🧬 LLM-Powered Microbiology Assistant

An intelligent assistant built using LangChain, LLaMA 3, and Adaptive Retrieval-Augmented Generation (RAG) to support microbiology students and faculty with syllabus guidance, scientific resources, and cumulative academic knowledge.
---

## 🎓 What Students Can Do

1. Ask about syllabus content  
2. Get explanations for microbiology topics  
3. Access resources like books, videos, and research papers  
4. Learn from previous students’ Q&A  
5. Review compiled questions from prior academic years  
6. View past students’ answers to commonly asked questions  

---

## 🧾 Project Overview


workflow 



This project uses **LangChain** to build an LLM-powered educational assistant tailored for a university's **Microbiology Department**.

The assistant can:

- Answer questions based on the microbiology syllabus  
- Summarize research literature and lab protocols  
- Provide curated study resources  
- Support cumulative academic learning by surfacing historical Q&A  

It is designed to help both **students** (for learning and exam prep) and **faculty** (for research, literature access, and data summarization).

---

## ⚙️ Technologies Used

- 🖥️ **Frontend**: [Streamlit](https://streamlit.io/)  
- 🧠 **Model**: [LLaMA 3 70B on Groq](https://groq.com/) – Fast inference  
- ☁️ **Hosting**: Firebase Hosting  
- 🔗 **LangChain** for orchestration
- 🧠 **Adaptive RAG**: Smart retrieval strategy that adjusts based on query type (factual, exploratory, or historical)


---

## 🔐 Guardrails: Off-Topic Filtering

To ensure the assistant stays academically relevant:

- Filters are applied to block unrelated queries (e.g., jokes, general chat, politics)  
- Helps maintain focus on microbiology syllabus and resources  
- Enhances safety and usefulness in educational settings  

---

## 💾 Caching: Local File-Based

To reduce latency and API costs:

- Frequently asked questions are cached locally in JSON  
- Prevents duplicate LLM calls for the same queries  
- Improves response time for repeat questions  

---

## 🚀 Deployment (Optional)

This app can be deployed using:

- [Streamlit Community Cloud](https://streamlit.io/cloud) (free, public hosting)  
- [Firebase Hosting](https://firebase.google.com/products/hosting)  
- [Render](https://render.com/) or [Fly.io](https://fly.io/) for backend/API

---

## 📂 Folder Structure (Example)

