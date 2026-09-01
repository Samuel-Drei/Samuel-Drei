# Samuel Andrei Tramontin Teixeira

Full-stack developer. I maintain two React Native apps in production, work on scaling a clinic management system built in React, and lead infrastructure hardening on our own Linux VPS.

[LinkedIn](https://linkedin.com/in/samuel-andrei) · [samuelandreit.teixeira@gmail.com](mailto:samuelandreit.teixeira@gmail.com)

---

## Projects

### RAG Pipeline v2.0
A retrieval-augmented generation system for semantic document search, built with a custom vector search and reranking layer.

I rebuilt the retrieval step to cut latency from 15.8s to 5.2s and reduce token cost by 67%, while keeping accuracy at 88%. The biggest lever was reranking candidates before sending them to the LLM instead of relying on raw vector similarity — most of the cost was being spent on context the model never needed.

`Python` `LangChain` `Vector DB`

### FisioTech — infrastructure & reliability
I maintain and scale the production infrastructure behind a clinic management system: CI/CD pipeline (GitHub Actions), server hardening (firewall, fail2ban, SSH key auth — cut exposed ports from 16 to 3), and incident response.

One incident worth mentioning: a WhatsApp integration was failing with HTTP 405 errors and unbounded reconnection attempts, which had locked clinics out of the system for close to three weeks by the time I traced it. Root cause was a missing backoff strategy on reconnects. Fixed with exponential backoff.

`React` `GitHub Actions` `Linux` `CI/CD`

### ConectAgro
A full-stack app connecting rural producers in Mato Grosso to infrastructure and logistics networks — built to work reliably on low-end devices and inconsistent connections, which shaped most of the architecture decisions.

`TypeScript` `React` `Capacitor.js`

---

## Stack

**Languages & frameworks:** TypeScript, JavaScript, Python, React, React Native, Next.js, Node.js
**AI/data:** RAG, LangChain, embeddings, vector databases
**Infra:** PostgreSQL, Supabase, Docker, GitHub Actions, Linux (VPS)

---

*Currently based in Mato Grosso, Brazil, studying Software Engineering at UTFPR.*
