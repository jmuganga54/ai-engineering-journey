# AI Engineering Journey

**From Python beginner to building real-world AI applications**

**Learning period:** 16 October 2026 – 15 January 2027 (92 days)  
**Study commitment:** 2–3 hours per day  
**Goal:** Develop practical foundations for junior AI engineering through consistent practice and three portfolio projects.

## About this repository

This repository documents my 92-day, project-based learning journey in AI engineering. I am starting with Python fundamentals and progressively learning how to build, test, evaluate and deploy useful AI applications.

The focus is **learning by building**. I will use free learning resources, write code regularly, reflect on what I understand and document projects that demonstrate my progress.

> **Current focus:** Month 1 — Python and software development foundations.  
> **Last updated:** 16 October 2026.

## Learning roadmap

| Stage | Dates | Main topics | Target milestone |
| --- | --- | --- | --- |
| **Month 1: Foundations** | 16 Oct – 15 Nov 2026 | Python, terminal, Git/GitHub, files, pandas, SQL, testing, basic APIs | Python data automation project |
| **Month 2: AI applications** | 16 Nov – 15 Dec 2026 | Machine learning, neural network basics, language models, prompting, embeddings, vector search and RAG | Document search and question-answering application |
| **Month 3: Engineering and portfolio** | 16 Dec 2026 – 15 Jan 2027 | FastAPI, tool calling, evaluation, security, Docker, deployment and documentation | End-to-end AI knowledge assistant |

### Learning path

`Python → Git and data handling → Machine learning foundations → AI model integration → Embeddings and RAG → FastAPI → Testing and evaluation → Deployment`

## Portfolio projects

The projects below are **planned or in progress**, not completed products. Each project will receive its own documentation, tests and demonstration as it develops.

### 1. Python Data Automation

**Problem:** Repetitive data cleaning and reporting can be slow and error-prone.  
**Goal:** Build a Python programme that reads a sample data file, checks for common issues, cleans fields and produces a summary report.  
**Core skills:** Python, file handling, pandas, data validation, automated tests and Git.  
**Planned location:** `projects/01-python-data-automation/`

**Definition of done:** The tool processes a documented sample dataset, handles invalid input, passes basic tests and has clear setup and usage instructions.

### 2. Document Search and RAG

**Problem:** Finding reliable answers across multiple documents takes time.  
**Goal:** Build a semantic search and document question-answering application that retrieves relevant passages and shows its sources.  
**Core skills:** Text processing, embeddings, Chroma, retrieval, language model integration and evaluation.  
**Planned location:** `projects/02-document-search-rag/`

**Definition of done:** The application retrieves useful passages, identifies sources, handles questions it cannot answer and is tested against a small question set.

### 3. AI Knowledge Assistant — Capstone

**Problem:** People need a simple interface for asking questions about a collection of documents.  
**Goal:** Build an end-to-end AI assistant with document retrieval, a backend API, a user interface, evaluation and a reproducible deployment workflow.  
**Core skills:** Python, FastAPI, RAG, model integration, testing, security basics, Docker and deployment.  
**Planned location:** `projects/03-ai-knowledge-assistant/`

**Definition of done:** A user can submit a question, receive a response grounded in retrieved documents, inspect supporting sources and follow documented instructions to run the application. Tests and evaluation results are included.

## Repository organisation

```text
ai-engineering-journey/
├── README.md
├── .gitignore
├── .env.example
├── roadmap/
│   ├── roadmap.md
│   └── resources.md
├── learning/
│   ├── month-01-python-foundations/
│   │   └── week-01-python-basics/
│   │       └── day-01-hello-world.py
│   ├── month-02-ml-and-ai/
│   └── month-03-production-ai/
├── projects/
│   ├── 01-python-data-automation/
│   ├── 02-document-search-rag/
│   └── 03-ai-knowledge-assistant/
├── progress/
│   ├── daily-log.md
│   ├── skills-checklist.md
│   └── weekly-reviews/
└── assets/
    └── screenshots/
```

Some folders and files will be created later, as they become relevant. Learning exercises go under `learning/`; complete applications go under `projects/`; reflections and reviews go under `progress/`.

## Progress dashboard

**Progress as of 16 October 2026:**

| Metric | Progress |
| --- | --- |
| Learning days completed | **1 / 92** |
| Portfolio projects completed | **0 / 3** |
| Current stage | Month 1 — Foundations |
| Current topic | Python input, output and string methods |

**Overall daily completion:** `completed learning days ÷ 92 × 100`

I record daily outcomes in [my learning log](progress/daily-log.md) and summarise my learning in `progress/weekly-reviews/`.

### Daily study routine

1. **Learn:** Follow the assigned lesson and take short notes.
2. **Practise:** Write and run the exercise myself, without relying on AI-generated code.
3. **Verify:** Test the result and explain the concepts in my own words.
4. **Document:** Update `progress/daily-log.md` with what I learned, built and found difficult.
5. **Commit:** Save meaningful changes in Git with a descriptive commit message.

A typical study session takes **2–3 hours**. Each week includes time for revision, debugging and catch-up.

## Getting started

To run a Python exercise locally on macOS, open a terminal in the repository folder:

```bash
# Optional: create and activate a virtual environment
python3 -m venv .venv
source .venv/bin/activate

# Run my first Python exercise (once this file exists)
python3 learning/month-01-python-foundations/week-01-python-basics/day-01-hello-world.py
```

Individual portfolio projects will have their own `README.md` files with specific installation, usage, test and demonstration instructions when completed.

## Primary free learning resources

| Topic | Resource |
| --- | --- |
| Python | [Harvard CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) |
| Python reference | [Official Python Tutorial](https://docs.python.org/3/tutorial/) |
| Git | [Pro Git book](https://git-scm.com/book/en/v2) |
| Data analysis | [Kaggle Learn](https://www.kaggle.com/learn) |
| Machine learning | [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) |
| Language models | [Hugging Face LLM Course](https://huggingface.co/learn/llm-course/) |
| Vector database | [Chroma documentation](https://docs.trychroma.com/) |
| APIs | [FastAPI documentation](https://fastapi.tiangolo.com/) |
| Containers | [Docker Get Started](https://docs.docker.com/get-started/) |

Day-by-day lesson links and reading notes are collected in `roadmap/resources.md`.

## Tools and technology

**Programming and data:** Python, pandas, NumPy, SQL  
**Development:** VS Code, terminal, Git, GitHub, pytest  
**AI and machine learning:** scikit-learn, pretrained models, embeddings, language model APIs  
**Applications:** Chroma, retrieval-augmented generation, FastAPI, a lightweight user interface  
**Production basics:** Docker, automated tests, evaluation, security practices and deployment

These are **learning targets**, not a claim that I already know every tool.

## Free-first AI policy

I will prioritise tools I can run locally and free educational resources. For semantic search, I plan to use local CPU embeddings and Chroma. When a real language model is unavailable, I can test application wiring with a deterministic mock client. Optional hosted AI APIs will only be used within genuinely available free usage limits; **I will not enable paid billing just to complete this roadmap**.

I will not commit secrets, API keys, personal information, confidential datasets or large generated model files to this repository. `.env` files and local data should be excluded through `.gitignore`.

## How I will judge success

By 15 January 2027, I aim to be able to:

- [ ] Write, organise, debug and test Python code.
- [ ] Use Git and GitHub confidently for a reproducible project workflow.
- [ ] Process data and explain fundamental machine learning concepts.
- [ ] Integrate a pretrained model or language model into an application.
- [ ] Build semantic search and a grounded document question-answering workflow.
- [ ] Explain embeddings, retrieval, prompting, common failure modes and evaluation.
- [ ] Expose an AI application through an API and a simple interface.
- [ ] Document how to run, test, evaluate and deploy an application.
- [ ] Present **three finished, well-documented portfolio projects**.

**Realistic outcome:** A strong practical foundation and portfolio to support junior-role applications, not mastery of every advanced AI engineering topic or a guarantee of employment.

---

*I will update this repository as I learn, build, test and improve.*
