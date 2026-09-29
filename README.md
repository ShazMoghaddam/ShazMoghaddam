Hi, I'm Shaz

Python and AI engineer based in London. I build data platforms that take messy, real-world input and turn it into something deployed, tested and usable: LLM-powered document extraction, ML anomaly detection, and analytics dashboards on FastAPI and Plotly Dash.

Trained through Imperial College London's Data Science Bootcamp (96% average). Looking for ML/AI engineering and data roles in London or remote.

Portfolio · LinkedIn · shaz.moghaddam@gmail.com

Featured projects
VoltScope: LLM extraction and validation for UK energy bills

Commercial energy bills arrive as PDFs and phone photos in every layout you can imagine. VoltScope sends each one to Claude for schema-constrained extraction into a fixed Pydantic model, then runs deterministic checks the LLM shouldn't be trusted with: MPAN digit counts, subtotal and VAT reconciliation, duplicate charges, estimated reads and contract renewal windows.

The design principle is simple: the LLM does the reading, plain Python does the checking. 50 golden-file tests on real anonymised supplier bills keep the extraction honest.

Python FastAPI Claude API Pydantic SQLite Docker

VoltEdge: energy intelligence platform

Multi-site energy monitoring with per-site isolation forest anomaly detection, causal root-cause analysis using the PC algorithm, Scope 2 emissions reporting, and a Claude assistant that answers questions like "what caused the spike at the London factory last Thursday?" Runs on 90 days of simulated data across four site types.

903 tests · JWT auth with role-based access · Live demo (free tier, give it up to a minute to wake up)

Python FastAPI Plotly Dash scikit-learn NetworkX Claude API Docker

ClinIQ: clinical trial site performance

Tracks enrolment velocity, site risk scores and protocol deviations for mid-sized CROs, with an AI insights layer on top. Built in five phases with 496 tests.

Python FastAPI Plotly Dash SQLAlchemy scikit-learn spaCy Claude API

SalaryAxis: UK salary benchmarks from ONS data

Takes ONS Annual Survey of Hours and Earnings data, adjusts it for CPI inflation, and serves salary benchmarks by region and occupation through a REST API and React dashboard, including gender pay gap trends over time.

Python Flask pandas SciPy React Docker

CVLens: NLP CV analyser

Parses PDF and Word CVs, detects sections, extracts skills with spaCy and generates readable quality feedback.

Python spaCy PyMuPDF python-docx

Lending Club: loan default prediction

Logistic regression model predicting loan default risk on Lending Club data.

<!-- Add one line with your key result here, e.g. the metric you optimised for and what it achieved -->

Python pandas scikit-learn

What I work with

Python pandas NumPy scikit-learn spaCy SQL FastAPI Flask Plotly Dash Streamlit Pydantic Docker Git pytest Claude API Render Railway

Also built

A set of small developer tools, each with a live demo: Regex Decoder, Cron Decoder, Python Exceptions and HTTP Status Codes.

I also ship Android apps and digital products on my own. You can find all of them on my website.

Open to full-time, contract and freelance work. If you're building something with data or LLMs, I'd like to hear about it.
