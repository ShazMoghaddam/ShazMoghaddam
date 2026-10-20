# Hi, I'm Shaz

Python and AI engineer based in London. I build data platforms that take messy, real-world input and turn it into something deployed, tested and usable: LLM-powered document extraction, ML anomaly detection, and analytics dashboards on FastAPI and Plotly Dash.

Trained through Imperial College London's Data Science Bootcamp (96% average). Looking for ML/AI engineering and data roles in London or remote.

[Portfolio](https://shazmoghaddam.github.io) · [LinkedIn](https://www.linkedin.com/in/shazmoghaddam/) · [DEV](https://dev.to/shazmoghaddam) · [Reddit](https://www.reddit.com/user/Aggravating_Pie2373/) · shaz.moghaddam@gmail.com

---

## Featured projects

### LedgerLet: Making Tax Digital for UK landlords *(in development)*

Making Tax Digital for Income Tax means many UK landlords now have to keep digital records and send HMRC an update every quarter. LedgerLet is the product I'm building for them: record income and expenses across every property at your ownership share, import bank statements as CSV with a preview and duplicate check, see each quarter in HMRC's own categories, and send it with a receipt you can keep.

It's built as a modular monolith with four layers (API, service, repository, model), and every phase has to pass its tests before the next one starts. Properties and the transactions core are done; CSV import and HMRC quarterly submissions are next. The repo is private while it's in development, but I've open-sourced the UX documentation approach as [ux-boards](https://github.com/ShazMoghaddam/ux-boards).

`Python` `FastAPI` `PostgreSQL` `SQLAlchemy` `Alembic` `React` `Vite` `Docker`

### [VoltScope](https://github.com/ShazMoghaddam/voltscope): LLM extraction and validation for UK energy bills

Commercial energy bills arrive as PDFs and phone photos in every layout you can imagine. VoltScope sends each one to Claude for schema-constrained extraction into a fixed Pydantic model, then runs deterministic checks the LLM shouldn't be trusted with: MPAN digit counts, subtotal and VAT reconciliation, duplicate charges, estimated reads and contract renewal windows.

The design principle is simple: the LLM does the reading, plain Python does the checking. 50 golden-file tests on real anonymised supplier bills keep the extraction honest.

`Python` `FastAPI` `Claude API` `Pydantic` `SQLite` `Docker`

### [VoltEdge](https://github.com/ShazMoghaddam/voltedge): energy intelligence platform

Multi-site energy monitoring with per-site isolation forest anomaly detection, causal root-cause analysis using the PC algorithm, Scope 2 emissions reporting, and a Claude assistant that answers questions like "what caused the spike at the London factory last Thursday?" Runs on 90 days of simulated data across four site types.

903 tests · JWT auth with role-based access · [Live demo](https://voltedge-1k6q.onrender.com) (free tier, give it up to a minute to wake up)

`Python` `FastAPI` `Plotly Dash` `scikit-learn` `NetworkX` `Claude API` `Docker`

### [ClinIQ](https://github.com/ShazMoghaddam/cliniq): clinical trial site performance

Tracks enrolment velocity, site risk scores and protocol deviations for mid-sized CROs, with an AI insights layer on top. Built in five phases with 496 tests.

`Python` `FastAPI` `Plotly Dash` `SQLAlchemy` `scikit-learn` `spaCy` `Claude API`

### [SalaryAxis](https://github.com/ShazMoghaddam/salaryaxis): UK salary benchmarks from ONS data

Takes ONS Annual Survey of Hours and Earnings data, adjusts it for CPI inflation, and serves salary benchmarks by region and occupation through a REST API and React dashboard, including gender pay gap trends over time.

`Python` `Flask` `pandas` `SciPy` `React` `Docker`

### [CVLens](https://github.com/ShazMoghaddam/CVLens): NLP CV analyser

Parses PDF and Word CVs, detects sections, extracts skills with spaCy and generates readable quality feedback.

`Python` `spaCy` `PyMuPDF` `python-docx`

### [Lending Club](https://github.com/ShazMoghaddam/Lending_Club_Loan_Project): loan default prediction

Logistic regression model predicting loan default risk on Lending Club data.
<!-- Add one line with your key result here, e.g. the metric you optimised for and what it achieved -->

`Python` `pandas` `scikit-learn`

---

## Open source

**[ux-boards](https://github.com/ShazMoghaddam/ux-boards):** turn one YAML file into UX documentation boards (information architecture, navigation by screen size, wireframes and a visual system with WCAG contrast checks), exported as HTML, PDF and PNG. [Live examples](https://shazmoghaddam.github.io/ux-boards/)

`Python` `Jinja2` `Playwright` `GitHub Actions`

**[Orbs](https://github.com/ShazMoghaddam/orbs):** ten morphing dot-formation animations for the web, from a Fibonacci sphere to a rolling torus, and any shape can morph into any other. One file, about 5 KB gzipped, no dependencies, themed with plain CSS. [Live demo](https://shazmoghaddam.github.io/orbs/) · [How I built it](https://dev.to/shazmoghaddam/how-i-built-morphing-dot-animations-with-plain-canvas-no-libraries-5-kb-127h)

`JavaScript` `Canvas`

**[Strata Symbol Kit](https://github.com/ShazMoghaddam/strata-symbols):** 183 layered-line symbols, letters and numbers for designers. Adjust the line count, angle and colour in the browser, then export clean SVG, PNG or a full sprite. [Live editor](https://shazmoghaddam.github.io/strata-symbols/)

`JavaScript` `Python` `SVG`

---

## Writing

- [How I built morphing dot animations with plain canvas, no libraries (5 KB)](https://dev.to/shazmoghaddam/how-i-built-morphing-dot-animations-with-plain-canvas-no-libraries-5-kb-127h) on DEV

---

## What I work with

`Python` `pandas` `NumPy` `Jupyter` `scikit-learn` `spaCy` `SQL` `PostgreSQL` `SQLite` `SQLAlchemy` `Alembic` `FastAPI` `Flask` `Plotly Dash` `Streamlit` `Pydantic` `JavaScript` `React` `Docker` `Git` `pytest` `GitHub Actions` `Playwright` `Claude API` `Render` `Railway`

---

## Also built

A set of small developer tools, each with a live demo: [Regex Decoder](https://shazmoghaddam.github.io/regex-decoder/), [Cron Decoder](https://shazmoghaddam.github.io/cron-decoder/), [Python Exceptions](https://shazmoghaddam.github.io/python-exceptions/), [HTTP Status Codes](https://shazmoghaddam.github.io/http-status-codes/), [HTTP Headers](https://shazmoghaddam.github.io/http-headers/) and [Tech Acronyms](https://shazmoghaddam.github.io/tech-acronyms/).

I've also published 7 apps on Google Play and sell digital products on my own. You can find all of them on [my website](https://shazmoghaddam.github.io).

---

Open to full-time, contract and freelance work. If you're building something with data or LLMs, I'd like to hear about it.
