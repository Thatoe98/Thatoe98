# Hi, I'm Thatoe Nyi 👋

**Final-year Computer Science student at Rangsit University (graduating May 2027), building LLM agents, RAG systems and machine-learning models, and shipping them for real users.**

I like taking an AI idea all the way to production: a clear spec, honest evaluation, a deployed service, and documentation someone else can follow.

📍 Bangkok, Thailand  
🎯 **Looking for an AI / ML / Data Science co-op internship from January 2027 (4+ months)**

[![Portfolio](https://img.shields.io/badge/Portfolio-thatoe--portfolio.vercel.app-1F3A68?style=flat-square&logo=vercel&logoColor=white)](https://thatoe-portfolio.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-thatoe--nyi--cs-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thatoe-nyi-cs)
[![Email](https://img.shields.io/badge/Email-thatoebkk%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:thatoebkk@gmail.com)

---

## ⭐ Featured projects

### 🏢 [Htake Than AI](https://github.com/Thatoe98/htake-than-ai): company AI assistant for a real client
A mobile-first web app where employees chat with an AI assistant in **Burmese or English** to log work, manage tasks and file daily reports, and the CEO gets a morning briefing.
- The assistant proposes tool calls, and **nothing is saved without a human approving a confirmation card**; permissions are re-checked on the server.
- Briefing **numbers come from SQL, and the LLM only writes the wording**, with a post-check that discards any number not in the facts.
- Per-call cost logging with a hard monthly spending cap, an audit log, and role checks in every server action.
- Requirements written feature by feature, with code, tests and commits tracing back to them.

`Next.js` `TypeScript` `Vercel AI SDK` `OpenAI` `PostgreSQL + pgvector` `Drizzle` `Docker Compose` `Vitest`

### 🤖 [Agentic Customer-Support System](https://github.com/Thatoe98/RAG_Agentic_Customer_Service_Messenger): live client deployment
A Facebook Messenger agent that answers customers from a business's own documents and hands off to a human on Telegram.
- Gemini function calling (knowledge search, human escalation) with a step cap.
- **RAG pipeline written from scratch:** document ingestion, chunking, embeddings and cosine-similarity search.
- A "trainer" agent lets the owner update the bot just by chatting with it.
- Async FastAPI webhooks with signature verification; deployed on a Linux VPS behind Nginx with HTTPS and systemd.

`Python` `FastAPI` `Gemini` `SQLite` `NumPy` `Docker`

### 🎙️ [Jarvis](https://github.com/Thatoe98/Facebook_and_tiktok_RAG_marketing_bot): multi-agent content pipeline
Turns a voice note into a bilingual social-media post grounded in real product data.
- Chained transcription, brainstorming, writing and image agents, with per-role model routing through LiteLLM.
- Product facts retrieved from pgvector, plus a human-approval state machine before anything is published.
- Multi-tenant schema with Alembic migrations, docker-compose and pytest.

`Python` `FastAPI` `LiteLLM` `Gemini` `PostgreSQL + pgvector` `Docker`

### 🛒 [Snap & Go](https://github.com/Thatoe98/snap_and_go_self_checkout_retail_stores): vision-based self-checkout
- Built a custom object-detection dataset from product videos, labelled in Roboflow, with lighting, blur and rotation augmentation.
- Trained YOLOv8n on a Colab GPU and served it through FastAPI with a configurable confidence threshold and QR payment-slip verification.

`Python` `PyTorch / YOLOv8` `OpenCV` `Roboflow` `FastAPI` `Supabase`

### 🔍 [Banking Fraud Detection](https://github.com/Thatoe98/data_science_and_ML_projects): unsupervised anomaly detection
- Explored 2,512 unlabelled bank transactions and standardized the transaction, balance and login features.
- Compared K-Means (elbow method, distance to centroid), DBSCAN and Isolation Forest to flag suspicious activity.

`Python` `scikit-learn` `pandas` `Seaborn`

### 🧑‍🤝‍🧑 [Face Recognition System](https://github.com/Thatoe98/celebrity_recognition)
- Recognizes 105 identities by cosine matching of Facenet512 embeddings, with no training needed; serves top-5 matches through a Flask API.

`Python` `TensorFlow / Keras (DeepFace)` `OpenCV` `Flask`

---

## 🔬 Research

**Chunking Quality vs. RAG Architecture**, senior research project at Rangsit University (finishing December 2026)  
A controlled experiment comparing chunking strategies across naive RAG, Self-RAG and agentic RAG, testing whether chunk-quality metrics predict answer quality and retrieval recall.

---

## 🗂️ More projects

| Project | What it is | Stack |
| --- | --- | --- |
| [Crimson Palace WebOS](https://github.com/Thatoe98/crimson_palace_restaurant_system) | Restaurant operations portal: KPI dashboard, POS, QR ordering, kitchen display, with PostgreSQL functions for KPI and cost analytics | Next.js, PostgreSQL, Prisma |
| [RestaurantOS](https://github.com/Thatoe98/restaurant_inventory_management_system) | Inventory, sales analytics and financial reports with CSV import and row-level security | Next.js, Supabase |
| [Blood Inventory System](https://github.com/Thatoe98/database_project_1) | Relational schema with summary views and triggers for stock and donor eligibility | PostgreSQL, SQL |
| [CampusLearn](https://github.com/Thatoe98/Campus_learn_blockchain_project) | Learn-to-earn dApp: ERC-20 rewards, soulbound NFT badges, Chainlink price feed | Solidity, ethers.js |
| [OpenAI Messenger Bot](https://github.com/Thatoe98/messenger_bot) | An early Facebook Messenger chatbot built on the OpenAI API | Python, OpenAI API |

---

## 🛠️ Tech stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=flat-square&logo=javascript&logoColor=F7DF1E)
![SQL](https://img.shields.io/badge/SQL-00758F?style=flat-square&logo=postgresql&logoColor=white)

**AI, ML & Data**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

**Backend, Data & Deployment**  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

**Frontend**  
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=flat-square&logo=prisma&logoColor=white)

---

## 📜 Certifications

- [Machine Learning Specialization](https://coursera.org/verify/specialization/EJZRO57O028E), DeepLearning.AI & Stanford Online (Oct 2026)
- Meta Data Analyst Professional Certificate
- IBM RAG and Agentic AI Professional Certificate (in progress)

---

## ⚡ Beyond the code

- 🎮 Ranking up in **Dota 2** or boss-hunting in **Black Myth: Wukong**
- 📖 Big fan of *JoJo's Bizarre Adventure* (Steel Ball Run is peak fiction)
- 🗣️ Burmese (native), English (fluent)

![Thatoe's GitHub stats](https://github-readme-stats.vercel.app/api?username=Thatoe98&show_icons=true&theme=tokyonight&hide_border=true)
