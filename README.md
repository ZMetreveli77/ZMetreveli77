# Hi, I'm Zuka Metreveli 👋

**Full-stack developer** in Tbilisi, working in **React** on the frontend and **Python (FastAPI / Flask)** on the backend, and lately building AI apps with retrieval and LLM agents.  
I'm a Computer Science & AI student at Business and Technology University (BTU), looking for internships, junior developer roles and hackathon teams.

🌐 **Portfolio: [metroz.me](https://metroz.me)** · 📍 Tbilisi, Georgia · 🗣️ Georgian, English

## 🚀 Featured projects

### 🔎 [CaseFile](https://github.com/ZMetreveli77/CaseFile): an AI investigation engine that cites its evidence
**[Live demo](https://casefile.metroz.me)** · Solo project · React, TypeScript, FastAPI, Qdrant, Gemini, Docker

Ask a question about a large document collection. CaseFile searches step by step, follows facts from one document to the next, and links every claim to the passage behind it. When sources disagree it says so, and when the evidence is missing it declines to answer.
- Hybrid search (dense embeddings + my own BM25, fused with Reciprocal Rank Fusion) over **78,730 passages** in Qdrant Cloud
- Tool-calling agent with citation validation, prompt-injection tests and a Gemini → Groq failsafe
- Evaluated on 60 questions: multi-hop accuracy went from **0.60 to 0.80** compared with a one-search baseline

> Free hosting: the first request can take about a minute to wake the server.

### ⚽ Grand Tour: fantasy football across Europe
**[Live demo](https://grandtour.metroz.me)** · React, Python

Seven games on one account: one for each of the top five leagues, one for the Champions League, and the Grand Tour itself, where a single 25-player squad spans all five leagues on a £200m budget. Each game has its own squad, points and mini-leagues.

### 📈 [BizLens](https://github.com/G10rga/BizLens): cash-flow forecasting for Georgian small businesses
[Live demo](https://bizlens.g1orga.dev) *(temporarily offline)* · Team project · React, Flask, SQLAlchemy, Prophet, RapidOCR

A bakery owner records sales at the till or photographs a fiscal receipt. BizLens sets that against rent, salaries and supplier payments, forecasts cash 30, 60 and 90 days out, and warns before it runs short. The forecast accounts for Orthodox holidays, fasting periods and tourist season. Available in Georgian and English.

### 🛂 [AI Skills Digital Passport](https://github.com/G10rga/AI-Skills-Digital-Passport): AI skills anyone can verify
[Live demo](https://aipassport.g1orga.dev) *(temporarily offline)* · BTU hackathon, team project (I built the core backend) · React, TanStack Start, FastAPI, Solidity, Ed25519

Each student keeps one permanent passport, and every confirmed skill issues a new version. Each version is hashed, signed by the university and anchored on-chain, so an employer can verify it with a code, a QR or the PDF itself, without logging in. Edited PDFs fail the check.

## 🛠️ Tech I work with
- **Frontend:** React, TypeScript, JavaScript, Vite, Tailwind, Sass
- **Backend:** Python, FastAPI, Flask, SQLAlchemy, SQLite
- **AI & data:** retrieval and hybrid search, LLM agents, Qdrant, forecasting (Prophet), OCR
- **Tooling:** Git & GitHub, Docker, pytest, Vitest

## 📫 Contact
🌐 [metroz.me](https://metroz.me) · 💼 [LinkedIn](https://www.linkedin.com/in/zuka-metreveli-111aa630b)
