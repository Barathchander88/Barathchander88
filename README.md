<img src="https://capsule-render.vercel.app/api?type=waving&color=0:412991,50:6D28D9,100:3FCF8E&height=170&section=header&text=Barath%20Chander%20E&fontSize=42&fontColor=ffffff&fontAlignY=36&desc=AI%20Engineer%20%26%20Full-Stack%20Developer&descSize=18&descAlignY=58" width="100%">

<p align="center">
I build <b>LLM-powered products end to end</b> — API integration, backend, data layer, deployment.<br>
Currently at <b>Hodos360 AI</b>, shipping AI features to external customers on Vercel and AWS.
</p>

<p align="center">
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white">
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white">
<img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white">
<img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white">
</p>
<p align="center">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white">
<img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white">
<img src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white">
<img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white">
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white">
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
</p>

---

## How I build conversational AI

```mermaid
flowchart LR
    U(["User"]) --> API["Backend API"]
    API --> D{"Needs stored data?"}
    D -->|yes| S[("Supabase")]
    D -->|no| P["Prompt + context"]
    S --> P
    P --> L["OpenAI / Gemini"]
    L --> M["Media generation"]
    L --> R(["Response"])
    M --> R
    R --> U

    classDef core fill:#412991,stroke:#8B5CF6,color:#ffffff
    classDef data fill:#3FCF8E,stroke:#1F7A52,color:#06281A
    classDef edge fill:#1F2937,stroke:#6B7280,color:#ffffff
    class L,M core
    class S,P data
    class API,D edge
```

Context is retrieved **conditionally** — records are pulled into the prompt only when the query needs them, rather than stuffing context into every request.

---

## What I build

<table>
<tr>
<td width="50%" valign="top">

### Conversational AI
Direct OpenAI and Gemini API calls in code. Multi-turn context handling and Supabase-backed retrieval.

</td>
<td width="50%" valign="top">

### Generative media
Images, ad creatives, and video via OpenAI, Gemini, and Seedance through the Kie.ai API layer.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Automation
Event-driven n8n workflows and GoHighLevel CRM automation across internal production systems.

</td>
<td width="50%" valign="top">

### Motion interfaces
React and Three.js — 3D, animation, and frontends that do more than sit still.

</td>
</tr>
</table>

---

## Selected work

| Project | What it is | Stack |
|---|---|---|
| [laaraasourcingindia](https://github.com/Barathchander88/laaraasourcingindia) | Live client website for a garment sourcing company | HTML · CSS · JS · PHP |

> [!NOTE]
> Chatbot and Three.js repos going public soon.

<details>
<summary><b>Background</b></summary>

<br>

**Hodos360 AI** — AI Engineer / Full-Stack Developer, Oct 2025 – present
**Zenanvibe** — Full-Stack Developer Intern, Jan – Sep 2025
**B.E. Computer Science and Design**, Erode Sengunthar Engineering College, 2025

Also work with C, C++, Embedded C and IoT systems from my engineering background.

</details>

---

<p align="center">
<a href="https://www.linkedin.com/in/barath-chander-eb99972227"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="mailto:barathchander88@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>
<p align="center"><sub>Tiruppur, Tamil Nadu, India</sub></p>
