# Hi, I'm Timur 👋  
**Full-Stack Developer | Applied Machine Learning, AI Tooling & Computer Vision**

I am a software engineer (York University B.Sc. CS) specializing in bridging the gap between backend automation and machine learning. I focus on building end-to-end pipelines—from data ingestion and model training to interactive web deployment.

---

### 🚀 Featured Projects

#### 🏗️ [Architecture Design Assistant](https://github.com/timuryesm/arch-assistant)
*A specialized AI tool for system design thinking — structured conversations, live diagrams, adversarial critique, and RAG-powered guidelines.*
- **Tech:** Node.js, Express, Next.js, Anthropic Claude API, LangChain, Mermaid.js, Voyage embeddings, localStorage.
- **Highlights:** Four specialized Claude system prompts (senior architect, diagram converter, technical writer, adversarial reviewer), LangChain LCEL chain composition, in-memory RAG pipeline with cosine similarity retrieval, session persistence without a database, four-panel UI with lifted state orchestration.
- **Architecture:** Stateless Express backend with five API routes, Next.js frontend with localStorage session history, Voyage embeddings for semantic chunk retrieval from uploaded PDF guidelines.
- **Key concepts:** Prompt engineering as product design, LLM statelessness and conversation management, multi-prompt AI systems, P0/P1/P2 adversarial design review, RAG with semantic search.

#### 🐛 [Bug Fixer — Autonomous LLM PR Generator](https://github.com/timuryesm/bug-fixer)
*An LLM-driven pipeline that reads GitHub issues, retrieves relevant code via FAISS, generates patches, validates them in a Docker sandbox, and opens pull requests autonomously.*
- **Tech:** Python, OpenAI API (`gpt-4o-mini`, `text-embedding-3-small`), FAISS, Docker, GitHub REST API, pytest, GitHub Actions.
- **Highlights:** Retrieval-augmented file selection over AST-level chunks, `ast.parse()` pre-flight patch validation, Docker-isolated test execution, delta-aware acceptance check distinguishing regressions, no-ops, and catastrophic failures from real fixes.
- **Architecture:** 9-stage pipeline (issue fetch → clone → chunk → embed → retrieve → generate → validate → sandbox-test → judge → PR), modular across six Python packages, CI on GitHub Actions.
- **Demo PRs:** [is_palindrome on buggy-calc](https://github.com/timuryesm/buggy-calc/pull/6) | [Job.\_\_lt\_\_ on schedule](https://github.com/timuryesm/schedule/pull/2) — 945-line single-file repo, bug located by the model from a symptom-only issue description.

#### 🧾 [Intelligent Invoice & Document Processing Pipeline](https://github.com/timuryesm/idp-pipeline)
*A production-shaped pipeline that ingests, extracts, validates, and reconciles invoice data, with a human-in-the-loop review dashboard.*
- **Tech:** Python, OpenAI Vision API, Pydantic, pdfplumber, PyMuPDF, SQLite, Streamlit, pytest.
- **Highlights:** Pluggable extraction layer (deterministic text parser with an AI vision fallback for scanned documents), `Decimal`-exact total reconciliation that auto-flags mismatches for human review, magic-byte file validation, and a 29-test suite.
- **Architecture:** Modular ingestion → extraction → validation → persistence, orchestrated end-to-end into a Streamlit dashboard with a pipeline queue, side-by-side review screen, and spend analytics.

#### 🏀 [NBA Win-Prediction Engine](https://github.com/timuryesm/nba-intensity-analysis)
*A full-stack ML project predicting season win totals using 5 years of historical efficiency data.*
- **Tech:** Python, Scikit-Learn, Streamlit, NBA API, Plotly.
- **Highlights:** Features a live interactive dashboard, automated data extraction pipeline, and an MAE of ~2.8 wins.
- **Links:** [Live Dashboard](https://nba-intensity-analysis-timuryesm.streamlit.app/) | [Project Presentation](https://timuryesm.github.io/nba-intensity-analysis/)


#### 📊 [Business Intelligence ML Capstone](https://github.com/timuryesm/ml-business-capstone)
*End-to-end data science pipeline focusing on business use-case interpretations.*
- **Tech:** Pandas, Scikit-Learn, Hyperparameter Tuning (GridSearch/Optuna).
- **Process:** Exploratory Data Analysis (EDA) → Feature Engineering → Model Comparison → Business Insights.

#### 🤖 [Bitrix24 Automation Showcase](https://github.com/timuryesm/bitrix-automation)
*A collection of production-grade scripts for business process automation.*
- **Tech:** PHP, Node.js, REST APIs, Telegram Bot API.
- **Impact:** Automated CRM workflows and communication triggers for enterprise-level efficiency.

---

### 🛠️ Tech Stack

**AI & Data Science:**  
`Python` `PyTorch` `NumPy` `Pandas` `Scikit-Learn` `OpenCV` `OpenAI API` `Anthropic Claude API` `LangChain` `FAISS` `Voyage embeddings` `Pydantic` `Matplotlib` `Plotly`

**Backend & Automation:**  
`Node.js` `Express` `PHP` `REST APIs` `Bitrix24 API` `GitHub API` `FastAPI` `SQLite` `pytest` `Telegram Bots`

**Web & DevOps:**  
`React` `Next.js` `JavaScript (ES6+)` `Docker` `GitLab CI` `GitHub Actions` `AWS (EC2/S3)` `Streamlit`

---

### 📈 Currently Exploring
- **AI Systems Design:** Multi-prompt architectures, LangChain orchestration, and RAG pipelines for production AI tooling.
- **LLM Engineering:** Prompt engineering as a product discipline — specialised prompts, output contracts, and adversarial evaluation.
- **Model Deployment:** Advanced FastAPI patterns and HuggingFace Spaces.
- **MLOps:** Versioning data and models to ensure reproducibility.
- **Edge AI:** Optimizing Computer Vision models for real-time performance.

---

### 📬 Connect with Me
- **LinkedIn:** [timuryesm](https://www.linkedin.com/in/timuryesm/)
- **Email:** [timuryesm@gmail.com](mailto:timuryesm@gmail.com)
- **Portfolio:** *TBU*

> "Building applied machine learning projects with clarity, rigor, and real-world impact."
