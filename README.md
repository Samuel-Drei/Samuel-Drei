<h1>Samuel Andrei Tramontin Teixeira</h1>

<p>
  <img src="https://img.shields.io/badge/React-087EA4?style=flat-square&labelColor=1a1a1a" height="22"/>
  <img src="https://img.shields.io/badge/React_Native-087EA4?style=flat-square&labelColor=1a1a1a" height="22"/>
  <img src="https://img.shields.io/badge/Next.js-white?style=flat-square&labelColor=1a1a1a" height="22"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&labelColor=1a1a1a" height="22"/>
  <img src="https://img.shields.io/badge/RAG_%2F_LangChain-6E56CF?style=flat-square&labelColor=1a1a1a" height="22"/>
</p>

Full-stack developer. I maintain two React Native apps in production, work on scaling a clinic management system built in React, and lead infrastructure hardening on our own Linux VPS.

**[LinkedIn](https://linkedin.com/in/samuel-andrei)** · **[Email](mailto:samuelandreit.teixeira@gmail.com)** · Mato Grosso, Brazil

<br>

## Projects

### 🔹 RAG Pipeline v2.0
A retrieval-augmented generation system for semantic document search, built with a custom vector search and reranking layer.

> Rebuilt the retrieval step to cut latency from **15.8s → 5.2s** and reduce token cost by **67%**, while keeping accuracy at **88%**. The biggest lever was reranking candidates before sending them to the LLM instead of relying on raw vector similarity — most of the cost was being spent on context the model never needed.

`Python` `LangChain` `Vector DB`

### 🔹 FisioTech — infrastructure & reliability
I maintain and scale the production infrastructure behind a clinic management system: CI/CD pipeline, server hardening, and incident response.

> Cut exposed network ports from **16 → 3** through firewall rules, fail2ban, and SSH key auth. Also traced a WhatsApp integration failure (HTTP 405, unbounded reconnects) that had locked clinics out of the system for close to three weeks — fixed with exponential backoff.

`React` `GitHub Actions` `Linux` `CI/CD`

### 🔹 ConectAgro
A full-stack app connecting rural producers in Mato Grosso to infrastructure and logistics networks.

> Built to work reliably on low-end devices and inconsistent connections, which shaped most of the architecture decisions.

`TypeScript` `React` `Capacitor.js`

<br>

## Stack

| | |
|---|---|
| **Languages & frameworks** | TypeScript · JavaScript · Python · React · React Native · Next.js · Node.js |
| **AI / data** | RAG · LangChain · embeddings · vector databases |
| **Infrastructure** | PostgreSQL · Supabase · Docker · GitHub Actions · Linux (VPS) |

<br>

<sub>Studying Software Engineering at UTFPR.</sub>
