🤖 Agentic AI Researcher App
An autonomous AI system designed to help researchers by discovering papers, extracting insights, fixing LaTeX errors, and generating ready-to-use PDFs — with memory of your past research.

---

📌 **Features**

📄 **Automated Paper Retrieval:** Finds relevant research papers from arXiv and other sources.
🧠 **Smart Research Analysis:** Reads and summarizes papers, extracting key points.
📚 **Latest References:** Ensures papers are backed by up-to-date citations.
⚙️ **LaTeX to PDF Conversion:** Automatically converts LaTeX into error-free PDFs.
🔍 **Self-Healing Error Fixing:** Detects and corrects LaTeX errors autonomously.
💾 **Chat Memory:** Saves every user interaction for continuity in future sessions.

---

🛠️ **Tech Stack**

| Category             | Tools & Services              |
| -------------------- | ----------------------------- |
| Programming Language | Python                        |
| Paper Retrieval      | arXiv API, Semantic Scholar   |
| AI & Reasoning       | LangGraph, Google GenAI, Groq |
| PDF & LaTeX Handling | PyLaTeX, pdflatex             |
| Frontend UI          | Streamlit                     |
| Environment Handling | python-dotenv                 |
| Runtime & Packaging  | uv                            |

---

📁 **Project Structure**

```
└── danishali22-ai-researcher/
    ├── README.md                # Project documentation
    ├── ai_researcher.py         # Core agent logic
    ├── ai_researcher_2.py       # Extended features
    ├── arxiv_tool.py            # Fetching papers from arXiv
    ├── frontend.py              # UI integration (Gradio/Streamlit)
    ├── pyproject.toml           # Project dependencies & config
    ├── read_pdf.py              # PDF reading & parsing
    ├── write_pdf.py             # LaTeX → PDF generation
    ├── .python-version          # Python runtime version
    └── output/                  # Generated papers
        ├── paper_20250919_145030.tex
        ├── paper_20250919_145239.tex
        └── paper_20250919_145336.tex
```

---

🔧 **Setup Instructions**

**Clone the Repository**

```bash
git clone https://github.com/danishali22/danishali22-ai-researcher.git
cd danishali22-ai-researcher
```

**Install Dependencies**

```bash
uv pip install -r pyproject.toml
```

**Configure Environment Variables**

```bash
cp .env.example .env
# Add API keys (Groq, Google GenAI, etc.)
```

**Run the App**

```bash
python frontend.py
```

---

🤖 **How It Works**

1. User enters a research interest.
2. Agent retrieves top relevant papers.
3. Papers are read, analyzed, and summarized.
4. Agent drafts a research paper in LaTeX with citations.
5. LaTeX errors are auto-detected and fixed.
6. Final PDF is generated and saved.
7. Memory stores all interactions for continuity.

---

📚 **What I Learned**

* Building autonomous research agents with LangGraph.
* Integrating knowledge retrieval (arXiv + Semantic Scholar).
* Handling LaTeX → PDF pipelines with error recovery.
* Designing memory-enabled research assistants.
* Creating smooth researcher-focused interfaces.

---

🙌 **Feedback**
If you find this project interesting or want to collaborate, feel free to open an issue or connect!

**GitHub:** danishali22

