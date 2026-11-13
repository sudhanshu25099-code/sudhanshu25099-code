<div align="center">
  <img src="./hero-banner.png" width="100%" alt="Sudhanshu Shekhar Jha, AI/ML builder and software engineer. I build AI systems for clinics, classrooms and overloaded APIs. Build, learn, experiment, ship. New Delhi, India.">
</div>

> **I don't build AI demos. I build systems around real problems.**

Computer Science Engineering student at the Faculty of Technology, University of Delhi. My work sits where a model has to be right: a student in crisis, a prescription on a clinic desk, a service absorbing a traffic spike.

<p>
  <a href="https://sudhanshu-shekhar-jha.me/"><img src="https://img.shields.io/badge/portfolio-sudhanshu--shekhar--jha.me-C2261B?style=flat-square&amp;labelColor=121110&amp;logoColor=EDEAE3" alt="Portfolio"></a>&nbsp;
  <a href="https://www.linkedin.com/in/sudhanshu-shekhar-jha-b0aaa9377/"><img src="https://img.shields.io/badge/linkedin-connect-C2261B?style=flat-square&amp;labelColor=121110&amp;logo=linkedin&amp;logoColor=EDEAE3" alt="LinkedIn"></a>&nbsp;
  <a href="https://github.com/sudhanshu25099-code"><img src="https://img.shields.io/badge/github-sudhanshu25099--code-C2261B?style=flat-square&amp;labelColor=121110&amp;logo=github&amp;logoColor=EDEAE3" alt="GitHub"></a>&nbsp;
  <a href="mailto:sudhanshushekharjha2007@gmail.com"><img src="https://img.shields.io/badge/email-sudhanshushekharjha2007%40gmail.com-C2261B?style=flat-square&amp;labelColor=121110&amp;logo=gmail&amp;logoColor=EDEAE3" alt="Email"></a>
</p>

## 01 &nbsp; Working principle

Good engineering starts with the problem, not the framework. Three rules I keep:

- **Empathy first** — Anxiety detection, queue bottlenecks, clinical admin. The problem picks the stack, not the other way round.
- **Latency is a feature** — Groq LPUs and lean token pipelines, so a conversation feels like one turn instead of a round trip.
- **Standards, or it stays a demo** — HL7 FHIR R4 bundles, clean SQL schemas, backends that hold up under concurrent load.

## 02 &nbsp; Right now

```
role      cse student, faculty of technology, university of delhi
focus     generative ai, nlp, clinical systems, low-latency inference
building  student wellness ai, clinical intake, ehr workspace, rate limiter
open to   ai/ml internships, hackathon teams, open source
```

## 03 &nbsp; Selected work

### 01 Student Wellness AI

Conversational support for students, with distress-signal triage and guided decompression. About 180 ms per reply on Groq.

```
user input  →  llama 3.3 / groq  →  signal triage  →  decompression
```

`Llama 3.3` `Groq` `Flask` `SQLAlchemy` `Tailwind`

[Live demo](https://student-wellness-app.onrender.com/) &nbsp;&nbsp; [Source](https://github.com/sudhanshu25099-code/student-wellness-app_GFG26)

---

### 02 AI Clinical Intake

Voice-first intake and prescription OCR that turn a consultation into an ABDM-aligned HL7 FHIR R4 bundle before the doctor sees the patient.

```
speech + document  →  gemini api  →  structured extraction  →  fhir r4 bundle  →  opd queue
```

`Gemini API` `Web Speech` `LayoutLM` `FastAPI` `React` `FHIR R4`

[Source](https://github.com/sudhanshu25099-code/Medkiosk-By_Blackops)

---

### 03 Clinical EHR

Administration, OPD, nursing triage, diagnostics and LLM summarisation in one workspace, on a 38-table MySQL schema.

```
streamlit  →  fastapi  →  groq llm layer  →  mysql 8 (38 tables)
```

`FastAPI` `Streamlit` `Groq` `MySQL` `SQLAlchemy` `Pydantic v2`

[Source](https://github.com/sudhanshu25099-code/patient-case-taking)

---

### 04 API Traffic Control

A distributed rate limiter for FastAPI. PostgreSQL stores the policy, Redis and atomic Lua enforce it per client, in O(1) time and memory.

```
request  →  asgi middleware  →  postgres (rule lookup)  →  redis lua (counter)  →  200 / 429
```

- **Fixed Window:** O(1) time & memory · 1–2 Redis ops/req · bursts up to 2× limit at window boundary
- **Token Bucket:** O(1) time & memory · 1 Redis Lua op/req · bursts to capacity, then steady rate

[Source](https://github.com/sudhanshu25099-code/api-traffic-control)

## 04 &nbsp; Stack

### AI & Machine Learning
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" height="38" alt="Python"/>&nbsp;
  <img src="https://img.shields.io/badge/Llama_3.3-0467DF?style=for-the-badge&logo=meta&logoColor=white" height="38" alt="Llama 3.3"/>&nbsp;
  <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white" height="38" alt="Groq"/>&nbsp;
  <img src="https://img.shields.io/badge/Gemini_API-8E75C2?style=for-the-badge&logo=googlegemini&logoColor=white" height="38" alt="Gemini API"/>&nbsp;
  <img src="https://img.shields.io/badge/NLP-FF6F00?style=for-the-badge" height="38" alt="NLP"/>&nbsp;
  <img src="https://img.shields.io/badge/HL7_FHIR_R4-E31837?style=for-the-badge" height="38" alt="HL7 FHIR R4"/>
</p>

### Web & Backend
<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" height="38" alt="FastAPI"/>&nbsp;
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" height="38" alt="Flask"/>&nbsp;
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" height="38" alt="React"/>&nbsp;
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" height="38" alt="Next.js"/>&nbsp;
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" height="38" alt="Streamlit"/>&nbsp;
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" height="38" alt="JavaScript"/>&nbsp;
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" height="38" alt="Tailwind CSS"/>
</p>

### Databases & DevOps
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" height="38" alt="PostgreSQL"/>&nbsp;
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" height="38" alt="MySQL"/>&nbsp;
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" height="38" alt="Redis"/>&nbsp;
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" height="38" alt="SQLite"/>&nbsp;
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" height="38" alt="SQLAlchemy"/>&nbsp;
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" height="38" alt="Docker"/>&nbsp;
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" height="38" alt="Git"/>
</p>

## 05 &nbsp; GitHub Activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=sudhanshu25099-code&amp;background=121110&amp;border=332E2B&amp;stroke=332E2B&amp;ring=E2402C&amp;fire=E2402C&amp;currStreakNum=EDEAE3&amp;sideNums=EDEAE3&amp;currStreakLabel=E2402C&amp;sideLabels=B8B0A8&amp;dates=8A837C" width="70%" alt="Contribution streak">
</p>

## 06 &nbsp; Horizon

- **Agentic AI:** Multi-agent orchestration that survives a failing tool
- **Retrieval:** Modular RAG with vector search, measured rather than assumed
- **Multimodal:** Speech and documents into one clean clinical record
- **Evaluation:** Automated test suites that run before anything ships

## 07 &nbsp; Contact

> **Bring me the problem. I'll build the system.**  
> Open to AI/ML internships, hackathon teams, and open source collaboration.

- 🌐 **Portfolio:** [sudhanshu-shekhar-jha.me](https://sudhanshu-shekhar-jha.me/)
- 💼 **LinkedIn:** [sudhanshu-shekhar-jha-b0aaa9377](https://www.linkedin.com/in/sudhanshu-shekhar-jha-b0aaa9377/)
- 🐙 **GitHub:** [sudhanshu25099-code](https://github.com/sudhanshu25099-code)
- ✉️ **Email:** [sudhanshushekharjha2007@gmail.com](mailto:sudhanshushekharjha2007@gmail.com)
