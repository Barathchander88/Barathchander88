<h1 align="center">Barath Chander E</h1>
<p align="center"><b>AI Engineer &amp; Full-Stack Developer</b><br>
I build LLM-powered products end to end — API integration, backend, data layer, deployment.</p>

<p align="center">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white">
<img src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white">
<img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white">
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white">
<img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white">
<img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white">
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white">
</p>

Currently at **Hodos360 AI**, shipping AI features to external customers on Vercel and AWS.

---

### How I build conversational AI

```mermaid
flowchart LR
    U([User]) --> API[Backend API]
    API --> D{Needs<br/>stored data?}
    D -- yes --> S[(Supabase)]
    S --> P[Prompt + context]
    D -- no --> P
    P --> L[OpenAI / Gemini]
    L --> M[Media generation<br/>images · ads · video]
    L --> R([Response])
    M --> R
    R --> U

    classDef core fill:#412991,stroke:#8B5CF6,color:#fff
    classDef data fill:#3FCF8E,stroke:#1F7A52,color:#06281A
    classDef edge fill:#1F2937,stroke:#6B7280,color:#fff
    class L,M core
    class S,P data
    class API,D edge
```

Context is retrieved **conditionally** — records are pulled into the prompt only when the query needs them, rather than stuffing context into every request.

---

### What I build

**Conversational AI, from scratch.** Direct OpenAI and Gemini API calls in code, multi-turn context handling, Supabase-backed retrieval.

**Generative media pipelines.** Images, ad creatives, and video via OpenAI, Gemini, and Seedance models through the Kie.ai API layer.

**Automation that replaces manual work.** Event-driven n8n workflows and GoHighLevel CRM automation across internal production systems.

**Interfaces with motion.** React and Three.js — 3D, animation, frontends that do more than sit still.

---

### Selected work

| Project | What it is | Stack |
|---|---|---|
| [laaraasourcingindia](https://github.com/Barathchander88/laaraasourcingindia) | Live client website for a garment sourcing company | HTML · CSS · JS · PHP |

> [!NOTE]
> Chatbot and Three.js repos going public soon.

---

<p align="center">
B.E. Computer Science and Design, 2025 · Tiruppur, Tamil Nadu, India<br>
<a href="https://www.linkedin.com/in/barath-chander-eb99972227">LinkedIn</a> · barathchander88@gmail.com
</p>
