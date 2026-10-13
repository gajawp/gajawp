<div align="center">

# Hi, I'm Preethi Gajawada 👋

### AI/ML Engineer · Software Engineer · NLP & LLM Researcher

**4+ years** building production AI and scalable backend systems at **Goldman Sachs** and **Morgan Stanley** ·
ML Engineer Intern at **InSightX Lab** · M.S. Computer Science at **Northeastern University** — GPA 4.0/4.0

📍 Seattle, Washington · 🟢 **Actively seeking full-time ML / AI and Software Engineering roles**

[![Email](https://img.shields.io/badge/Email-gajawada.p%40northeastern.edu-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gajawada.p@northeastern.edu)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Preethi_Gajawada-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/preethi-gajawada-4b6824169/)

</div>

---

## 🙋‍♀️ About me

I'm an engineer who works where **large language models, retrieval systems, and dependable software** meet.
I've shipped GenAI knowledge assistants and semantic search used across 160+ workflows, built backends that
process 500K+ records a day, and done research that **placed 3rd in an ACL shared task**.

- 🔬 **Research:** counter-narrative generation, LLM-as-a-Judge evaluation, fairness-aware retrieval, medical image segmentation
- 🏗️ **Engineering:** RAG pipelines, distributed systems, microservices, ML pipelines on AWS
- 🧑‍🏫 **Teaching:** TA for Software Engineering and Program Design Paradigm at Northeastern
- 📝 **Service:** Reviewer for NeurIPS 2026 JUDGE papers; Area Chair for selected ACL papers

---

## 🏆 Highlights

- 🥉 **3rd place globally** at the **ACL LT-EDI 2026** shared task on counter-narrative generation
- 🎓 **Top-performing student across all semesters** of the Master's program (**GPA 4.0/4.0**)
- 🥇 **Top-ranked undergraduate in a cohort of 1,000 students** (GPA 9.27/10)
- 📄 Publications in **ACL (LT-EDI 2026)**, the **International Journal of IoT**, and accepted at **IEEE UEMCON**

---

## 💼 Experience

**🍎 InSightX Lab** — *ML Engineer Intern* · Seattle, WA · *Jan 2026 – Present*
- Built a **DSPy-based multilingual, multimodal counter-narrative system** using LLM pipelines, RAG, and prompt optimization to improve fairness and bias mitigation.
- Designed **LLM-as-a-Judge evaluation pipelines** with multi-objective reward functions to optimize for quality, safety, and fairness.
- Built the DSPy RAG pipeline for the **ACL LT-EDI** Counter-Narrative Generation Shared Task, which **ranked 3rd** on the official leaderboard.

**🎓 Northeastern University** — *Teaching Assistant* · Seattle, WA · *Jan 2026 – Present*
- TA for **Software Engineering** and **Program Design Paradigm**, mentoring students on system design and clean architecture.

**🏦 Goldman Sachs** — *Software Engineer* · Hyderabad, India · *Oct 2023 – Jul 2025*
- Architected a **GenAI-powered knowledge assistant** (RAG, LangChain, GPT-4, embeddings) for semantic search across **10K+ documents**, cutting manual effort by **45%**.
- Designed **semantic retrieval pipelines** (TF-IDF, sentence-transformer embeddings, similarity scoring), reducing analysis time by **40%**.
- Built and deployed **end-to-end ML pipelines on AWS** with **FastAPI** inference services, improving latency by **25%** across **160+ workflows**.
- Built high-performance **Java / Spring Boot** RESTful microservices with optimized concurrency, caching, and asynchronous processing.

**🏛️ Morgan Stanley** — *Software Engineer* · Bangalore, India · *May 2021 – Sep 2023*
- Built multi-threaded, data-intensive **Java backend systems** processing **500K+ daily records** with **99.99% uptime**.
- Modernized legacy monoliths into **Java 8 / Spring Boot microservices**, doubling scalability and cutting infrastructure costs by **80%**.
- Designed data-driven monitoring and optimization pipelines that improved system efficiency by **30%**.

---

## 📚 Research & publications

| Work | Venue | Status |
|---|---|---|
| **NEUNI@LT-EDI 2026: Counter Narrative Generation on Homophobic and Transphobic Comments** — fine-tuning-free prompt optimization; English & Tamil; multidimensional LLM-as-a-Judge evaluation. **3rd place globally.** | ACL · LT-EDI 2026 | Published, Jul 2026 |
| **Machine Learning-Based Framework for Detecting Unauthorized IoT Devices** — Random Forest on TCP/IP traffic features plus device whitelisting; **~96% detection accuracy**. | International Journal of IoT | Published, Jun 2025 |
| **AI-Powered Health Monitoring and Clinical Assistance Chatbot** — safety-aware, multilingual RAG chatbot with privacy-preserving tokenization and LLM guardrails. | IEEE UEMCON | Accepted |
| **Deep Learning Framework for Ovarian Cancer Segmentation and Classification** — segmentation-guided ROI classification with CNNs and vision transformers. | — | Manuscript in preparation |

---

## 🚀 Featured projects

### 🩺 [Ovarian Tumor Segmentation & Classification](https://github.com/gajawp/OvarianCancer)
`PyTorch` `Computer Vision` `Vision Transformers` `Medical Imaging`
- Benchmarked **7 segmentation architectures** (U-Net++, Attention U-Net, DeepLabV3+, TransUNet, SegFormer, DSNet, DS2Net); **DS2Net led with Dice 0.837 / IoU 0.754**.
- Built a **segmentation-guided ROI classifier** (DS2Net + MTA-Swin) and compared it with ResNet-50, DenseNet-121, EfficientNet-B3, ViT-B/16, and Swin-T.
- Ran controlled ablations, k-fold cross-validation, and multi-seed experiments; the final model reached **0.87 ROC-AUC**.

### 🏥 [HealthBridge AI — Clinical Assistance Chatbot](https://github.com/gajawp/HealthCareMonitoringMobilitySystem) · *accepted at IEEE UEMCON*
`RAG` `LLMs` `Streamlit` `Security`
- A multilingual, voice-enabled RAG assistant for patients, caregivers, and clinicians, with role- and patient-level authorization enforced **before** retrieval.
- Privacy-preserving identity tokenization, bcrypt authentication, audit logging, and guardrails against prompt injection and data leakage.
- Evaluated on 100 test cases: **96.7% factual accuracy, 100% authorization accuracy**, ~4 s mean latency.

### 🗣️ [Multilingual Counter-Narrative Generation](https://github.com/gajawp/counterNarrativeGeneration) · *3rd place, ACL LT-EDI 2026*
`DSPy` `GPT-4o` `COPRO` `NLP`
- A DSPy pipeline that generates respectful responses to hate speech in **English and Tamil**, with prompts optimized by **COPRO**.
- Scored with custom reward functions (safety, empathy, grounding, non-confrontation, NLI checks) plus LLM-judge and reference-based metrics.

### ⚖️ [LLM-as-a-Judge Evaluation Framework](https://github.com/gajawp/LLMAsAJudgeFramework)
`DSPy` `OpenAI` `Anthropic` `Ollama`
- A pluggable framework where generator and judge LLMs are swapped purely through config (OpenAI, Anthropic, or local Ollama models) — batch CSV evaluation, judge scoring, and tests.

### 🔍 [FairSearch-arXiv — Bias-Aware RAG](https://github.com/gajawp/Fairness)
`RAG` `ChromaDB` `FairLearn` `Embeddings`
- A fairness-aware retrieval system over **50K+ arXiv papers** using MiniLM embeddings, ChromaDB, and **MMR re-ranking** to reduce institutional bias.
- Evaluated with Precision, Recall, and NDCG alongside fairness metrics (selection-rate ratio, parity difference), with an interactive Streamlit dashboard.

### 🚗 [RideShare Dispatch Simulator](https://github.com/gajawp/RideShareDispatchSimulator)
`Java` `Concurrency` `Multithreading` `Design Patterns`
- An event-driven ride-dispatch simulator with asynchronous events, priority-based scheduling, and **thread-safe driver reservation**, built with Strategy, Factory, and Observer patterns and covered by unit tests.

<details>
<summary><b>More projects</b></summary>

- **Sentiment Analysis for Large-Scale Product Reviews** — a supervised NLP model on 50K+ Amazon reviews (TF-IDF, scikit-learn) reaching **88% accuracy**.
- **Satellite Image Classification** — transfer learning (ResNet / EfficientNet) to classify land-use patterns at **96% accuracy**.
- **Memory-Optimized Cache System** — LRU/LFU eviction in C++ with **O(1)** access and updates, using hash maps and doubly linked lists.

</details>

---

## 🛠️ Tech stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

**ML / AI**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)

**GenAI / LLMs**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![DSPy](https://img.shields.io/badge/DSPy-6E40C9?style=flat)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=flat&logo=anthropic&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat)

**Backend & Frameworks**
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)

**Data & Databases**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat&logo=neo4j&logoColor=white)

**Cloud & DevOps**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

**Concepts:** RAG · multi-agent systems · LLM evaluation (LLM-as-a-Judge) · prompt optimization (COPRO) · transformers ·
embeddings & semantic search · evaluation metrics (Precision, Recall, F1, NDCG) · distributed systems ·
event-driven architecture · asynchronous processing · microservices · system design · OOP & design patterns

---

## 🎓 Education

**Northeastern University, Khoury College of Computer Sciences** — Seattle, WA
*M.S. Computer Science (Data Science)* · GPA **4.0 / 4.0** · Sep 2025 – Dec 2026 (expected)
Coursework: Machine Learning, Distributed Systems, Cloud Computing, Operating Systems, Programming Design Paradigm, Algorithms

**Undergraduate degree** — graduated **top-ranked in a cohort of 1,000 students** · GPA **9.27 / 10**

---

<div align="center">

### 🤝 Let's connect

I'm actively looking for **ML / AI Engineering** and **Software Engineering** roles.
If you're hiring or want to collaborate on research, I'd love to hear from you!

[![Email](https://img.shields.io/badge/gajawada.p%40northeastern.edu-D14836?style=flat&logo=gmail&logoColor=white)](mailto:gajawada.p@northeastern.edu)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/preethi-gajawada-4b6824169/)

</div>
