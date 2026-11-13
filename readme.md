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

| the rule | what it means |
|:--|:--|
| **Empathy first** | Anxiety detection, queue bottlenecks, clinical admin. The problem picks the stack, not the other way round. |
| **Latency is a feature** | Groq LPUs and lean token pipelines, so a conversation feels like one turn instead of a round trip. |
| **Standards, or it stays a demo** | HL7 FHIR R4 bundles, clean SQL schemas, backends that hold up under concurrent load. |

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

### 02 AI Clinical Intake

Voice-first intake and prescription OCR that turn a consultation into an ABDM-aligned HL7 FHIR R4 bundle before the doctor sees the patient.

```
speech + document  →  gemini api  →  structured extraction  →  fhir r4 bundle  →  opd queue
```

`Gemini API` `Web Speech` `LayoutLM` `FastAPI` `React` `FHIR R4`

[Source](https://github.com/sudhanshu25099-code/Medkiosk-By_Blackops)

### 03 Clinical EHR

Administration, OPD, nursing triage, diagnostics and LLM summarisation in one workspace, on a 38-table MySQL schema.

```
streamlit  →  fastapi  →  groq llm layer  →  mysql 8 (38 tables)
```

`FastAPI` `Streamlit` `Groq` `MySQL` `SQLAlchemy` `Pydantic v2`

[Source](https://github.com/sudhanshu25099-code/patient-case-taking)

### 04 API Traffic Control

A distributed rate limiter for FastAPI. PostgreSQL stores the policy, Redis and atomic Lua enforce it per client, in O(1) time and memory.

```
request  →  asgi middleware  →  postgres (rule lookup)  →  redis lua (counter)  →  200 / 429
```

| algorithm | time | memory | redis ops per request | under burst |
|:--|:--|:--|:--|:--|
| fixed window | O(1) | O(1) | 1 to 2 | up to 2x the limit at the boundary |
| token bucket | O(1) | O(1) | 1 | bursts to capacity, then a steady rate |

[Source](https://github.com/sudhanshu25099-code/api-traffic-control)

## 04 &nbsp; Stack

| ai and generative | web and backend | data and infrastructure |
|:--|:--|:--|
| Llama 3.3, Groq, Gemini API, NLP, RAG, embeddings | FastAPI, Flask, React 19, Next.js, Streamlit, Tailwind | PostgreSQL, MySQL, Redis, SQLAlchemy, Docker, Git |

Healthcare work runs through HL7 FHIR R4 bundles and ABDM-aligned records, with Web Speech and OCR at the intake edge.

## 05 &nbsp; GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sudhanshu25099-code&amp;show_icons=true&amp;include_all_commits=true&amp;count_private=true&amp;bg_color=121110&amp;title_color=E2402C&amp;icon_color=E2402C&amp;text_color=B8B0A8&amp;border_color=332E2B&amp;ring_color=C2261B" width="49%" alt="GitHub statistics for sudhanshu25099-code"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sudhanshu25099-code&amp;layout=compact&amp;langs_count=8&amp;bg_color=121110&amp;title_color=E2402C&amp;text_color=B8B0A8&amp;border_color=332E2B" width="49%" alt="Most used languages">
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=sudhanshu25099-code&amp;background=121110&amp;border=332E2B&amp;stroke=332E2B&amp;ring=E2402C&amp;fire=E2402C&amp;currStreakNum=EDEAE3&amp;sideNums=EDEAE3&amp;currStreakLabel=E2402C&amp;sideLabels=B8B0A8&amp;dates=8A837C" width="70%" alt="Contribution streak">
</p>

## 06 &nbsp; Horizon

| area | what I'm working on |
|:--|:--|
| agentic ai | multi-agent orchestration that survives a failing tool |
| retrieval | modular RAG with vector search, measured rather than assumed |
| multimodal | speech and documents into one clean clinical record |
| evaluation | automated suites that run before anything ships |

## 07 &nbsp; Contact

<div align="center">
  <img src="./cta.png" width="100%" alt="Bring me the problem. I'll build the system. Open to AI/ML internships, hackathon teams and open source. sudhanshushekharjha2007@gmail.com">
</div>

AI/ML internships, hackathon teams, open source, or a system that needs to stop falling over. The inbox is open.

[Email](mailto:sudhanshushekharjha2007@gmail.com) &nbsp;&nbsp; [Portfolio](https://sudhanshu-shekhar-jha.me/) &nbsp;&nbsp; [LinkedIn](https://www.linkedin.com/in/sudhanshu-shekhar-jha-b0aaa9377/) &nbsp;&nbsp; [GitHub](https://github.com/sudhanshu25099-code)
