# AI-Resume-Analyzer
# 📄🤖 AI Resume Analyzer & ATS Optimizer

An intelligent, AI-powered web application designed to analyze resumes, compare them against specific job descriptions, calculate ATS (Applicant Tracking System) match scores, and provide actionable suggestions to help candidates land more interviews.

---

## 🚀 Key Features

- **📄 Multi-format Resume Parsing:** Supports uploading resumes in `.pdf` and `.docx` formats.
- **🎯 ATS Score Calculation:** Uses semantic search and LLMs to score how well a resume matches a given Job Description (JD).
- **💡 Detailed AI Feedback:** Generates tailored suggestions to improve summary, work experience bullet points, and formatting.
- **🔑 Skill Gap Analysis:** Highlights matching skills, missing critical keywords, and soft skills needed for the role.
- **📝 Bullet Point Rewriter:** Automatically rewrites weak resume bullet points using the **X-Y-Z formula** (Accomplished [X] as measured by [Y], by doing [Z]).
- **📊 Interactive Dashboard:** Visual representation of match scores, keyword density, and category-wise evaluation.

---

## 🛠️ Tech Stack

- **Frontend:** [Streamlit](https://streamlit.io/) (or React.js / Next.js)
- **Backend:** Python / FastAPI
- **LLM / AI Framework:** OpenAI GPT-4 / LangChain / LlamaIndex
- **Document Processing:** `pdfplumber`, `PyPDF2`, `python-docx`
- **Data Visualization:** Plotly / Matplotlib

---

## 📂 Project Structure

```text
ai-resume-analyzer/
├── assets/                  # Screenshots, logos, and demo images
├── src/
│   ├── components/          # UI components / Streamlit views
│   ├── parsers/             # PDF and DOCX parsing logic
│   ├── services/            # OpenAI API integration & prompts
│   └── utils/               # Helper functions & text cleaning
├── .env.example             # Example environment variables
├── app.py                   # Main application entry point
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
