<!-- Header -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,60:302b63,100:0f0c29&height=160&section=header&text=Raja%20Nayak&fontSize=56&fontColor=fff&fontAlignY=42&desc=Full-Stack%20Developer%20%7C%20AI%2FGenAI%20Engineer%20%7C%20Distributed%20Systems&descAlignY=65&descColor=a78bfa&animation=twinkling" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2800&pause=800&color=A78BFA&center=true&vCenter=true&multiline=true&repeat=true&width=800&height=85&lines=Building+voice+agents+that+talk+back+in+%3C400ms;Shipping+multi-agent+LLM+pipelines+at+scale;RAG+systems+with+98%25%2B+context+recall;Currently%3A+Fullstack+Dev+Intern+%40+GrowthGear" alt="Typing SVG" />

</div>

---

> Full-stack developer comfortable across the stack: React/Next.js on the frontend, Node.js/Express on the backend, and distributed, event-driven systems on AWS.
> Currently based in **Gurugram, Haryana** open to remote or relocation.

<div align="center">

### 🟢 Actively open to Backend / Fullstack / AI Engineer roles

[![Email](https://img.shields.io/badge/Email%20Me-nayakraja151%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nayakraja151@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nayakraja/)
[![LeetCode](https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/Raja_Nayak123/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-a78bfa?style=for-the-badge&logo=vercel&logoColor=white)](https://raja-dev.vercel.app/)

</div>

---

## What I've shipped by the numbers

| | | | |
|:---:|:---:|:---:|:---:|
| **<400ms** | **98%** | **96%+** | **225+** |
| End-to-end latency on a multilingual clinical voice agent | Booking race conditions eliminated via atomic Redis locks | Medical intent recognition accuracy | LeetCode problems solved |

---

## Experience

### 🏥 Fullstack Developer Intern — **GrowthGear** · *Jul 2026 – Present (Remote)*

- Architected a multilingual (Hindi/English) voice agent with **LiveKit** and **OpenAI LLMs** to autonomously route clinical calls, achieving **<400ms** end-to-end latency.
- Built a speech pipeline with **Sarvam AI** (STT/TTS) and **Silero VAD** for real-time barge-in handling and **96%+** medical intent recognition accuracy.
- Implemented multi-agent tool calling with atomic **Redis** locks, eliminating **98%** of booking race conditions across **2,500+** slots.
- Added SIP call escalation to route edge-case calls to human agents when automated handling failed.

### 🤖 Fullstack Developer Intern — **Xponentium** · *Jul 2025 – Feb 2026 (Gurugram)*

- Designed and productionized a **15-agent GPT-4o pipeline** with function calling, structured outputs, and RAG context via **Qdrant**, supporting **1,000+** concurrent job pipelines.
- Built an LLM evaluation harness to catch output regressions before each deployment, replacing manual spot-checks.
- Shipped a production real-time voice interview platform with **LiveKit WebRTC**, **Deepgram**, and **Cartesia**, achieving **p95 latency under 500ms**.
- Integrated the **JDoodle API** for live code execution during interviews, cutting recruiter review time by **60%** across 1,000+ job postings.
- Built the session-management, transcript-generation, and secure video-storage backend (Node.js, Express, PostgreSQL, GCS) powering the platform.

---

## Projects worth looking at

<summary><h3>🎙️ VoiceQuery AI &nbsp;<img src="https://img.shields.io/badge/NEW-brightgreen?style=flat-square"/> &nbsp; <a href="https://github.com/rajaNayak123">GitHub</a> · Demo</h3></summary>

Real-time Voice RAG system built with **LiveKit**, **Groq LLM**, and **Sarvam AI** for sub-second document Q&A with live barge-in interruption.
Hybrid retrieval pipeline in **Qdrant** combining dense vector + BM25 search with cross-encoder re-ranking.
Redis semantic caching for repeat-query latency. End-to-end latency tracing via **OpenTelemetry** to pinpoint bottlenecks.

`LiveKit` `Groq` `Sarvam AI` `Qdrant` `Redis` `OpenTelemetry`

**📊 Impact metrics**

| Metric | Result |
|---|---|
| Context recall (hybrid retrieval + re-ranking) | **98%** |
| Repeat-query latency (Redis semantic cache) | **99.6% faster** → <5ms |
| Query response | Sub-second, with live barge-in |
| Observability | Full trace coverage via OpenTelemetry |


<summary><h3>🗂️ Distributed File System &nbsp;<img src="https://img.shields.io/badge/NEW-brightgreen?style=flat-square"/> &nbsp; <a href="https://github.com/rajaNayak123">GitHub</a> · Demo</h3></summary>

Direct-to-S3 presigned multipart uploads to offload byte streaming from the server, eliminating server-side I/O and memory bottlenecks.
Event-driven pipeline via **AWS SQS + DLQs** for async SHA-256 checksums, enabling zero-loss processing with automated retries.
SHA-256 deduplication using **DynamoDB** idempotency locks to prevent duplicate-write race conditions.
Redis-based rate limiting protects upload endpoints from abuse.

`AWS S3` `SQS` `DynamoDB` `Redis` `Node.js`

**📊 Impact metrics**

| Metric | Result |
|---|---|
| Storage cost reduction (SHA-256 dedup) | **35%** |
| Processing reliability | **Zero-loss**, 5-attempt automated retries |
| Server-side I/O | Eliminated via direct-to-S3 presigned uploads |
| Duplicate-write race conditions | Prevented via DynamoDB idempotency locks |

<summary><h3>🎬 AI-Powered SaaS Media Platform — <a href="https://github.com/rajaNayak123/cloudinary-saas">GitHub</a> · <a href="https://cloudinary-saas-self.vercel.app/sign-up">Live Demo</a></h3></summary>

AI-driven media optimization engine across 10+ social media presets. Multi-tenant SaaS with RBAC and collaborative commenting.
Secure delivery via password-protected links and time-expiring tokens.

`Next.js` `Cloudinary` `Prisma` `PostgreSQL` `Clerk` `Razorpay`

**📊 Impact metrics**

| Metric | Result |
|---|---|
| Manual asset prep time | **80% faster** |
| Unauthorized access blocked | **99%** |
| Concurrent users supported | **50+** |


---

## 🛠️ Tech Stack

**Languages**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Shadcn](https://img.shields.io/badge/Shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=white)

**Backend & Systems**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Microservices](https://img.shields.io/badge/Microservices-1A1A2E?style=flat-square&logo=kubernetes&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)

**DevOps & CI/CD**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

**Cloud & Storage**

![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![AWS SQS](https://img.shields.io/badge/AWS_SQS-FF4F8B?style=flat-square&logo=amazonsqs&logoColor=white)
![Google Cloud Storage](https://img.shields.io/badge/Google_Cloud_Storage-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)

**GenAI / LLM / Voice AI**

![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF6B35?style=flat-square&logo=buffer&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![LiveKit](https://img.shields.io/badge/LiveKit-FF2D55?style=flat-square&logo=webrtc&logoColor=white)
![AI Agents](https://img.shields.io/badge/AI_Agents-00A67E?style=flat-square&logo=probot&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-5A67D8?style=flat-square&logo=anthropic&logoColor=white)

---

## GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=rajaNayak123&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa&text_color=c9d1d9&rank_icon=github&hide=stars&cache_seconds=1800" height="170"/>
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rajaNayak123&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=c9d1d9&langs_count=6&cache_seconds=1800" height="170"/>

  <br/>

  <img src="https://streak-stats.demolab.com/?user=rajaNayak123&theme=tokyonight&hide_border=true&background=0d1117&ring=a78bfa&fire=a78bfa&currStreakLabel=a78bfa" height="170"/>

  <br/>

  <img src="https://github-readme-activity-graph.vercel.app/graph?username=rajaNayak123&theme=tokyo-night&bg_color=0d1117&color=a78bfa&line=a78bfa&point=ffffff&hide_border=true" width="90%"/>

</div>

<!--
  Animated contribution snake — requires a GitHub Action in this repo to generate
  the snake SVG (see: https://github.com/Platane/snk). Once set up, this renders
  your contribution graph "eaten" by an animated snake.
-->
<div align="center">
  <img src="https://raw.githubusercontent.com/rajaNayak123/rajaNayak123/output/github-contribution-grid-snake.svg" width="90%" alt="snake animation" />
</div>

---

## Quick profile

| | |
|---|---|
| 🎓 **Education** | B.Tech CSE · Polaris School of Technology (Starex University) · CGPA **9.23** |
| 📍 **Location** | Gurugram, Haryana, India |
| 🗓️ **Graduating** | June 2027 |
| 💼 **Experience** | Fullstack Dev Intern @ GrowthGear (current) · Fullstack Dev Intern @ Xponentium |
| 🏆 **Achievements** | 225+ LeetCode problems · 110+ public repos · GitHub Pull Shark |
| 🔍 **Open to** | Backend, Fullstack, AI/GenAI Engineer — internship or full-time |
| ⚡ **Reply time** | Usually within a few hours |

---

## If you're building something ambitious, let's talk.

I'm not just looking for a job. I'm looking for a problem worth solving.

If you're building at scale, moving fast, or pushing into AI-native products, I'd love to hear about it.

<div align="center">

[![Email](https://img.shields.io/badge/nayakraja151%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nayakraja151@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nayakraja/)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/NayakRaja200)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/nayakraja200/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,60:302b63,100:0f0c29&height=100&section=footer&animation=twinkling" width="100%"/>

</div>
