<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:080d1a,50:1a4d7a,100:6b3aab&height=200&section=header&text=Ichrak%20Ennaceur&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=AI%20Engineer%20%C2%B7%20AI%20Consultant%20%C2%B7%20Applied%20Researcher%20in%20Gen%20AI&descAlignY=58&descSize=17&animation=fadeIn"/>

<p>
  <img src="https://img.shields.io/badge/🔬%20PhD%20Candidate-UCBL%20%2F%20LIRIS-6b3aab?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/⚙️%20AI%20Engineer-Inokufu-1a4d7a?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/📍%20Based%20in-Lyon%2C%20France-0f9a8d?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/💼%20Open%20to-Full--time%20%7C%20Lyon%20·%20Paris-00c896?style=for-the-badge"/>
</p>

<p>
  <a href="mailto:ichraknaceurr@gmail.com">
    <img src="https://img.shields.io/badge/Email-ichraknaceurr%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/ichrak-ennaceur-8979b0114/">
    <img src="https://img.shields.io/badge/LinkedIn-Ichrak%20Ennaceur-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://ichrak.dev">
    <img src="https://img.shields.io/badge/Portfolio-ichrak.dev-1a4d7a?style=flat-square&logo=globe&logoColor=white"/>
  </a>
  <a href="https://medium.com/@ichraknaceurr">
    <img src="https://img.shields.io/badge/Medium-@ichraknaceurr-000000?style=flat-square&logo=medium&logoColor=white"/>
  </a>
</p>

</div>

---

## 🧠 About Me

I'm an **AI Engineer, AI Consultant & Industrial PhD Candidate** at Université Claude Bernard Lyon 1 (LIRIS lab / Inokufu), specializing in **Generative AI**, **RAG architectures**, **LLM evaluation**, and **Recommendation Systems**.

I design and build **AI systems end-to-end** — from data pipelines and embedding strategies to LLM-powered APIs in production — with a strong focus on reliability, hallucination analysis, and evaluation rigor. I also teach Data Science and Machine Learning at Polytech Lyon / UCBL.

```python
ichrak = {
    "role"        : ["AI Engineer", "AI Consultant", "PhD Researcher", "Lecturer"],
    "research"    : ["RAG", "Hallucination Evaluation", "BERT4Rec", "LLM for Recommender Systems"],
    "expertise"   : ["Generative AI", "LLM Orchestration", "LLMOps", "Multi-Agent Systems", "NLP"],
    "stack"       : ["Python", "FastAPI", "LangGraph", "Claude API", "OpenAI", "Docker"],
    "publications": 4,
    "languages"   : ["French", "English", "Arabic"],
    "status"      : "Open to full-time — Lyon · Paris · Remote"
}
```

---

## 🔬 Research & Publications

| Year | Paper | Venue | Note |
|------|-------|-------|------|
| 2026 | **Diagnosing Hallucinations in RAG-Based Educational Recommendation Systems: A Controlled Comparative Study** | ISMIS 2026 | |
| 2026 | **CLARE : un cadre de recommandation d'objets d'apprentissage intégrant un RAG centré sur les compétences** | EGC 2026 | |
| 2025 | **CLARE: A Category-Aware RAG-Based Framework for Recommending Learning Objects** | WISE 2025 | |
| 2025 | **Prompt-Based Recommendation with In-Context Learning and Category-Enriched Modeling** | AICCSA 2025 | 🏆 Best Paper |

> **PhD thesis** (2023–2026): *"Generative AI-based Recommendation Systems for Educational Platforms"* — CIFRE industrial thesis co-supervised by LIRIS lab and Inokufu, combining BERT4Rec, RAG architectures, and LLM evaluation for EdTech.

---

## 🏛️ Academic Service

- **Technical Committee Chair** — AICCSA 2025 (ACS/IEEE International Conference)
- **Technical Committee Chair** — AICCSA 2026
- **Technical Committee Chair** — APWebWAIM 2026 (Asia Pacific Web & Web-Age Information Management)

---

## 🚀 Featured Projects

### 🎓 [CourseRAG API](https://github.com/inokufu/COURSERAGAPI)
> Semantic course retrieval + LLM-powered recommendations for EdTech

`FastAPI` `FAISS` `Sentence-Transformers` `OpenAI` `Anthropic` `Hexagonal Architecture`

Hexagonal architecture with pluggable vector backends (FAISS / Qdrant / Milvus) and LLM adapters (OpenAI / Anthropic). Designed for production deployment in educational platforms.

---

### 🔍 [RAG Hallucination Evaluator](https://github.com/Ichraknaceur/rag-hallucination-eval)
> End-to-end framework for evaluating and correcting hallucinations in RAG pipelines

`Claude API` `LangGraph` `ChromaDB` `FastAPI` `Docker`

Uses Claude API as an LLM-as-a-Judge with an iterative generate → evaluate → correct loop. Measures groundedness, faithfulness, and relevance. Directly tied to PhD research on hallucination analysis.

---

### 🎯 [BERT4Rec + RAG Recommender](https://github.com/Ichraknaceur/bert4rec-rag-recommender)
> Hybrid recommendation system combining sequential models with retrieval-augmented generation

`Python` `PyTorch` `BERT4Rec` `RAG` `FAISS` `FastAPI`

End-to-end pipeline integrating user behavior sequences (BERT4Rec) with contextual RAG for educational content recommendations. Backbone of the WISE 2025 and AICCSA 2025 publications.

---

### 🏢 [Enterprise Knowledge Assistant](https://github.com/Ichraknaceur/Entreprise-assistant)
> Production-oriented RAG system for enterprise internal knowledge bases

`FastAPI` `Milvus` `RAG` `Python` `Docker`

Clean layered architecture, source-backed answers, and Milvus vector retrieval. Built for enterprise adoption with a focus on traceability and explainability.

---

### 📡 [CareerSignal](https://github.com/Ichraknaceur/career-signal)
> AI-powered job search operating system

`Python` `LangGraph` `Claude API` `OpenAI` `FastAPI` `Streamlit` `Playwright` `SQLite` `Docker` `GitHub Actions`

Multi-agent platform covering content generation (Medium + LinkedIn), editorial scheduling with autopublish, LinkedIn outreach and networking, job tracking, and technical watch. Hexagonal architecture with domain-driven design: `app/` · `domain/` · `services/` · `storage/` · `observability/`.

---

### ⚙️ [FastAPI Hexagonal Template](https://github.com/Ichraknaceur/fastapi-hexagonal-template)
> Production-ready FastAPI template with hexagonal (clean) architecture

`Python` `FastAPI` `Docker` `PostgreSQL` `pytest` `GitHub Actions`

Domain-driven, testable, and CI/CD-ready. Used as the foundation for multiple freelance projects. Designed to separate business logic from infrastructure from day one.

---

## 🛠️ Tech Stack

**Generative AI & LLMs**

![Claude API](https://img.shields.io/badge/Claude%20API-D4A017?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-0f9a8d?style=flat-square)
![Fine--tuning](https://img.shields.io/badge/Fine--tuning%20LoRA%2FQLoRA-6b3aab?style=flat-square)

**ML & Recommendation**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![BERT4Rec](https://img.shields.io/badge/BERT4Rec-1a4d7a?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square)

**Evaluation & LLMOps**

![LLM-as-a-Judge](https://img.shields.io/badge/LLM--as--a--Judge-1a4d7a?style=flat-square)
![RAGAS](https://img.shields.io/badge/RAGAS-6b3aab?style=flat-square)
![Langfuse](https://img.shields.io/badge/Langfuse-0f9a8d?style=flat-square)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![W&B](https://img.shields.io/badge/W%26B-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)

**Backend & Infra**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## 💼 Experience

| Period | Role | Company | Type |
|--------|------|---------|------|
| 2022 – Present | AI Engineer & Research Scientist | Inokufu · Lyon | Full-time |
| 2024 – Present | Lecturer — Data Science & AI | Polytech Lyon / UCBL | Teaching |
| 6 months | Lead AI Engineer — Sales Forecasting Platform | MathildeCreations | Freelance |
| 6 months | Generative AI Engineer — LLM Content Evaluation | ContentCrea | Freelance |
| 2020 – 2022 | Lead Data Scientist — NLP & Audio AI | 1waycom · Tunis | Full-time |

**At Inokufu**: architected a hybrid BERT4Rec + RAG recommendation engine, built LLM-as-a-Judge evaluation pipelines for hallucination detection, contributed to the open-source Learning Records Converter (xAPI, SCORM, IMS Caliper), and co-authored 4 peer-reviewed papers.

---

## 🎓 Education

| Degree | Institution | Period |
|--------|-------------|--------|
| PhD in AI — Industrial Thesis CIFRE | UCBL / LIRIS · Lyon | 2023 – 2026 |
| Master's in Data Science & Engineering | University of Sfax | 2019 – 2021 |
| Bachelor's in Computer Science | University of Sfax | 2015 – 2019 |

---

## ✍️ Writing

I publish technical articles on [Medium](https://medium.com/@ichraknaceurr) about LLMs, RAG, and AI engineering in production:

- [Why Prompt Engineering Is a Crucial Step in Maximizing AI Efficiency](https://medium.com/@ichraknaceurr/why-prompt-engineering-is-a-crucial-step-in-maximizing-ai-efficiency-e0650c48961e)
- [Building Smarter LLMs with RAG: From Documents to Answers](https://medium.com/@ichraknaceurr/building-smarter-llms-with-rag-from-documents-to-answers-b9474c412ab1)
- [The Honest AI KPI Nobody Puts on the Slide](https://medium.com/@ichraknaceurr/the-honest-ai-kpi-nobody-puts-on-the-slide-were-measuring-the-wrong-things-and-we-know-it-bd672034bdb8)

---

## 📊 GitHub Stats

<div align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=Ichraknaceur&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6b3aab&icon_color=0f9a8d&text_color=ffffff"/>
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ichraknaceur&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6b3aab&text_color=ffffff"/>
</div>

---

## 🎯 Currently

- 📖 Completing my PhD thesis on **RAG + Hallucination Evaluation for Recommender Systems**
- 🔨 Building open-source AI tooling to share applied research
- 🏛️ Serving on the Technical Committee of **AICCSA 2026** and **APWebWAIM 2026**
- ✍️ Writing on **Medium** about production LLM engineering
- 💬 Open to **full-time opportunities** in AI Engineering, Gen AI Consulting, or Applied Research — Lyon · Paris · Remote

---

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:6b3aab,50:1a4d7a,100:080d1a&height=100&section=footer"/>
</div>
