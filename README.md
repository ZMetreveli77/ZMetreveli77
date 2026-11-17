# Hi, I'm Zuka Metreveli

I'm a full-stack developer in Tbilisi and a Computer Science & AI student at Business and Technology University (BTU). I mostly work with React on the front end and Python on the back end, and lately I've been building AI apps that search through documents and back up what they say.

I'm looking for internships, junior developer roles and hackathon teams.

My portfolio is at [metroz.me](https://metroz.me). I speak Georgian and English.

## What I've been building

### [CaseFile](https://github.com/ZMetreveli77/CaseFile)
An AI investigation engine that cites its evidence. [Try it live](https://casefile.metroz.me) (it's on free hosting, so the first request can take about a minute while the server wakes up).

You ask a question about a large collection of documents, and CaseFile works through it step by step, following facts from one document to the next. Every claim in the answer links to the passage it came from. If sources disagree, it tells you; if the evidence isn't there, it says so instead of making something up.

I built this one solo. It searches 78,730 passages in Qdrant using a mix of embeddings and my own BM25 implementation, and on a 60-question evaluation the agent got multi-hop questions right 80% of the time, up from 60% with a single search.

*React, TypeScript, FastAPI, Qdrant, Gemini, Docker*

### Grand Tour
Fantasy football across Europe. [Try it live](https://grandtour.metroz.me).

There are seven games on one account: one for each of the top five leagues, one for the Champions League, and the Grand Tour itself, where you build a single 25-player squad from all five leagues on a £200m budget. Each game has its own squad, points and mini-leagues.

*React, Python*

### [BizLens](https://github.com/G10rga/BizLens)
Cash-flow forecasting for small businesses in Georgia. Built with a team. The [live demo](https://bizlens.g1orga.dev) is offline for now.

Picture a bakery owner who logs sales at the till or snaps a photo of a fiscal receipt. BizLens weighs that against rent, salaries and supplier payments, forecasts cash 30, 60 and 90 days ahead, and warns them before money runs short. The forecast knows about Orthodox holidays, fasting periods and tourist season, and the app works in Georgian and English.

*React, Flask, SQLAlchemy, Prophet, RapidOCR*

### [AI Skills Digital Passport](https://github.com/G10rga/AI-Skills-Digital-Passport)
A record of AI skills that anyone can verify. We built it as a team for the BTU AI Skills Digital Passport hackathon, and I wrote the core backend. The [live demo](https://aipassport.g1orga.dev) is offline for now.

Every student has one permanent passport, and each confirmed skill adds a new version. Each version is hashed, signed by the university and anchored on-chain, so an employer can check it with a code, a QR code or the PDF itself, with no login needed. If someone edits the PDF, the check fails.

*React, TanStack Start, FastAPI, Solidity, Ed25519*

## Tools I use
- Front end: React, TypeScript, JavaScript, Vite, Tailwind, Sass
- Back end: Python, FastAPI, Flask, SQLAlchemy, SQLite
- AI and data: search and retrieval, LLM agents, Qdrant, forecasting with Prophet, OCR
- Everything else: Git, Docker, pytest, Vitest

## Get in touch
You can find me on [LinkedIn](https://www.linkedin.com/in/zuka-metreveli) or through my portfolio at [metroz.me](https://metroz.me).
