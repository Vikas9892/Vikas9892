<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f1720,100:1155CC&height=180&section=header&text=Vikas%20Tiwari&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%7C%20Full-Stack%2C%20Systems%20%26%20AI&descAlignY=58&descSize=18&descColor=e2e8f0" width="100%"/>

<a href="https://www.linkedin.com/in/vikas-tiwari-71b5482a7">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:vikast4843@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://leetcode.com/u/vikas7871/">
  <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/>
</a>
<a href="https://codeforces.com/profile/Vikas9140">
  <img src="https://img.shields.io/badge/Codeforces-445588?style=for-the-badge&logo=codeforces&logoColor=white"/>
</a>
<a href="https://www.codechef.com/users/smack_angel_65">
  <img src="https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/Open%20to%20Software%20Engineering%20Internships-2ea44f?style=for-the-badge"/>

</div>

<br/>

## About Me

I'm a B.Tech Information Technology student at IIIT Bhopal who learns by building things fully, not partially — I'd rather ship one system I understand end-to-end than clone ten tutorials I don't. That instinct is why I built a key-value store from raw TCP sockets instead of just using Redis, and why I built an evaluation harness for my RAG pipeline instead of assuming it worked because it "looked right" once.

I build systems end-to-end and **measure** whether they actually work, rather than assuming it — from a C++ key-value store with custom networking and concurrency, to a retrieval-augmented generation pipeline with its own evaluation harness, to full-stack platforms with real CI/CD gates.

- 🎓 B.Tech Information Technology @ **IIIT Bhopal** (2023 – 2027) · CGPA 8.43
- 🧠 **Codeforces Specialist** · **CodeChef 4★** · 500+ DSA problems solved
- 🔭 Currently building a multimodal product-intelligence backend (FastAPI, vector search, ML embeddings)
- 🌱 Learning by extending my own projects rather than starting over each time
- 💬 Ask me about async architectures, epoll servers, or hybrid retrieval design
- 📫 Reach me at [vikast4843@gmail.com](mailto:vikast4843@gmail.com) or [LinkedIn](https://www.linkedin.com/in/vikas-tiwari-71b5482a7)

<br/>

## Featured Projects

<table width="100%">
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/Vikas9892/KV_STORE">🗄️ Distributed Key-Value Store</a></h3>

A networked key-value store built from scratch in C++ — blocking and non-blocking (epoll, edge-triggered) servers, thread-pool concurrency with `shared_mutex`, and write-ahead logging with crash-safe recovery.

<img src="https://img.shields.io/badge/-C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/> <img src="https://img.shields.io/badge/-TCP%2FSockets-333333?style=flat-square"/> <img src="https://img.shields.io/badge/-epoll-333333?style=flat-square"/> <img src="https://img.shields.io/badge/-Multithreading-333333?style=flat-square"/>

**Real benchmarks:** 9,619 ops/sec (1 connection) · 4,831 ops/sec sustained @ 1,000 concurrent connections · 410ms crash recovery, zero data loss

</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/Vikas9892/rag_evaluation">🔍 RAG Evaluation System</a></h3>

A retrieval-augmented generation pipeline built without LangChain — hybrid dense (FAISS) + sparse (BM25) retrieval fused via Reciprocal Rank Fusion, with a dedicated evaluation harness for retrieval and faithfulness metrics.

<img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/-FAISS-4285F4?style=flat-square"/> <img src="https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/-AWS%20Lambda-FF9900?style=flat-square&logo=amazonaws&logoColor=white"/>

**289 tests · 87% coverage** · deployed as a streaming service on AWS Lambda

</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/Vikas9892/nifty-portfolio-optimizer">📈 Nifty Portfolio Optimizer</a></h3>

A full-stack portfolio optimization platform with an asynchronous job architecture, a circuit breaker around external APIs, and a CI/CD pipeline gating merges on real test coverage.

<img src="https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black"/> <img src="https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/> <img src="https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>

**163 tests · 80% coverage gate** · [Live demo ↗](https://nifty-portfolio-optimizer.vercel.app)

</td>
<td width="50%" valign="top">
<h3>🧩 Product Intelligence Engine <sub>(in progress)</sub></h3>

A multimodal product-catalog backend — a FastAPI service with a layered architecture (API/services/repositories/models), PostgreSQL storage, and async image ingestion. Currently extending with text/image embeddings (BGE, CLIP) indexed in Qdrant for hybrid semantic search and LLM-based structured metadata extraction.

<img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/-Qdrant-DC244C?style=flat-square"/>

**Phase 1 (backend skeleton) complete and tested** · embeddings + hybrid search in progress

</td>
</tr>
</table>

<br/>

## Tech Stack

**Languages**  
![C++](https://img.shields.io/badge/-C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend & Systems**  
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![AWS Lambda](https://img.shields.io/badge/-AWS%20Lambda-FF9900?style=flat-square&logo=amazonaws&logoColor=white)

**Frontend**  
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Redux](https://img.shields.io/badge/-Redux-764ABC?style=flat-square&logo=redux&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/-Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Data & AI/ML**  
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![FAISS](https://img.shields.io/badge/-FAISS-4285F4?style=flat-square) ![Qdrant](https://img.shields.io/badge/-Qdrant-DC244C?style=flat-square)

**Tools**  
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![CMake](https://img.shields.io/badge/-CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)

<br/>

## GitHub Stats

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=Vikas9892&show_icons=true&theme=default&hide_border=true&cache_seconds=86400"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Vikas9892&layout=compact&hide_border=true&cache_seconds=86400"/>
</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Vikas9892&hide_border=true"/>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f1720,100:1155CC&height=100&section=footer" width="100%"/>
