# Hi, I'm Umar Khan 👋

**Full-Stack Software Engineer** building secure, production healthcare software and AI-powered web apps.

- 🏥 Full-Stack Engineer at **Ingenio Care**: multi-tenant healthcare platform (PHI, RBAC, scheduling, billing, claims, telehealth)
- 🤖 Building **[Sunnah Lens](https://sunnahlens.com)**: RAG-powered semantic search over 29,653 hadith
- 🎓 B.S. Computer Science, **University of Illinois Chicago** (2025)
- 🌎 Based in the Chicago area · open to relocation

[![Portfolio](https://img.shields.io/badge/Portfolio-000?style=for-the-badge&logo=vercel&logoColor=white)](https://umarahmedkhan.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/umarkhan394/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:khanumar394@gmail.com)

---

## 🛠 Tech Stack

**Languages:** TypeScript · JavaScript · Python · Java · Go · Scala · C/C++
**Frontend:** React · Next.js · Flutter
**Backend:** Node.js · Express · FastAPI · Django
**Data & AI:** PostgreSQL · pgvector · RAG · Gemini / OpenAI APIs · Apache Spark · Hadoop
**Cloud & DevOps:** AWS · Docker · GitHub Actions

---

## 🚀 Featured Projects

### [Sunnah Lens](https://sunnahlens.com)
AI search engine over 29,653 hadith from the six major collections. You ask a question in plain English and get a grounded answer with citations.
- RAG pipeline: LLM keyword extraction → Gemini embeddings → pgvector HNSW top-k retrieval → answer streamed over SSE
- Guardrails restrict answers to the retrieved sources, require inline `[n]` citations, and say so when the sources don't cover a question
- Embedding cache and per-IP rate limiting keep API costs under control

`Next.js` `TypeScript` `FastAPI` `PostgreSQL` `pgvector` `Gemini`

### [LLM Pipeline](https://github.com/umar-dim/LLM-Pipeline)
Distributed LLM training pipeline for corpora too large for one machine's memory.
- BPE tokenization, vocabulary building, and embeddings parallelized across Hadoop MapReduce and Spark on AWS EMR
- Distributed transformer training that tracks loss, gradient norms, and cluster utilization

`Scala` `Apache Spark` `AWS EMR` `Hadoop` `DeepLearning4j`

### [Evently](https://github.com/umar-dim/EVENTLY)
Event discovery app with ML-personalized recommendations. Engagement grew **40%**.
- Recommendation model trained on users' RSVP history
- Scraping pipeline that aggregates real-time event data from multiple sources
- Fraud-resistant QR code check-in

`React` `Node.js` `Python` `Machine Learning`

### [Smart Grocery](https://github.com/umar-dim/Smart-Grocery)
Cross-platform app that combines recipe discovery with grocery-list management. Recommendations raised engagement **35%** and recipe conversions **25%**.

`Flutter` `Dart` `SQL`

### [Nostalgia Threads](https://github.com/umar-dim/Nostalgia-Threads)
Social platform for sharing cultural memories by region and tag. Uses a Trie for tag autocomplete and a priority queue to rank trending posts.

`Django` `React` `Java` `REST APIs`

---

## 📊 GitHub Stats

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=umar-dim&show_icons=true&hide_border=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=umar-dim&layout=compact&hide_border=true" alt="Top languages" />
</p>

---

💬 **Open to full-stack and AI/ML software engineering roles.** Reach out at [khanumar394@gmail.com](mailto:khanumar394@gmail.com).
