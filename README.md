<div align="center">

```
 ███╗   ██╗██╗████████╗███████╗███████╗██╗  ██╗    ███████╗ █████╗ ██╗███╗   ██╗██╗
 ████╗  ██║██║╚══██╔══╝██╔════╝██╔════╝██║  ██║    ██╔════╝██╔══██╗██║████╗  ██║██║
 ██╔██╗ ██║██║   ██║   █████╗  ███████╗███████║    ███████╗███████║██║██╔██╗ ██║██║
 ██║╚██╗██║██║   ██║   ██╔══╝  ╚════██║██╔══██║    ╚════██║██╔══██║██║██║╚██╗██║██║
 ██║ ╚████║██║   ██║   ███████╗███████║██║  ██║    ███████║██║  ██║██║██║ ╚████║██║
 ╚═╝  ╚═══╝╚═╝   ╚═╝   ╚══════╝╚══════╝╚═╝  ╚═╝    ╚══════╝╚═╝  ╚═╝╚═╝╚═╝  ╚═══╝╚═╝
```

</div>

<h1 align="center">Nitesh Saini</h1>

<p align="center">
  <b>AI & Backend Engineer</b><br/>
  <sub>Building things that scale — LLM pipelines, distributed microservices, and automation that runs in production</sub>
</p>

<p align="center">
  <a href="mailto:nitesh.saini.dev@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://linkedin.com/in/nitesh-saini-b936b1257" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://github.com/niteshsaini9568" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://portfolio-frontend-peach-one.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-FF5722?style=flat&logo=google-chrome&logoColor=white" />
  </a>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=niteshsaini9568&label=Profile%20views&color=0e75b6&style=flat" />
</p>

---

## `whoami`

Integrated M.Tech student in CS & AI at **RGIPT** (Institution of National Importance), 4th year, graduating May 2027 — shipping real backend systems since my second year. I gravitate toward the hard parts: distributed architecture, job queues, caching layers, retrieval pipelines, and making things actually reliable at scale.

Currently **AI Engineer** at **MantriAI** (Bangalore), building the AI layer of a hiring platform — and previously **Member of Technical Staff** at **GeeksforGeeks**, working on systems design for the Code Editor infrastructure.

Right now I'm deep in:

- **PreCall @ MantriAI** — an AI hiring pipeline: Express/MongoDB services that embed CVs and JDs, vector-score a top-K shortlist, then LLM-screen it into match scores, gaps and bucketed interview questions. Plus a FastAPI engine that turns a JD + discovery-call transcript into 10 grounded follow-up questions
- **Recruiter automation** — Playwright profile extractors (LinkedIn, GitHub, Hirist/IIMjobs) and idempotent Zoho Recruit sync that pushes screening notes and attaches resumes across candidate records
- **CampusHire** — a college placement portal with role-based access, a Go/Node microservices backend on PostgreSQL + Redis, Docker/Kubernetes deployment, off-campus job scraping agents via n8n, and an admin analytics panel on AWS S3/EC2

I write TypeScript, Node.js and Python day-to-day. I know my way around Golang, PostgreSQL, Redis, Docker, LLM APIs, and anything AWS. When I'm not writing backend code I'm doing competitive programming — 400+ problems across LeetCode and GFG.

---

## Experience

| Role | Company | Period | What I did |
|------|---------|--------|------------|
| **AI Engineer** | MantriAI | May 2026 – Present | Built the PreCall hiring pipeline — CV/JD embeddings, vector top-K shortlisting, LLM screening and interview-question generation; shipped a FastAPI grounded-question engine over scraped company review intel; automated recruiter ops with profile extractors and Zoho Recruit sync |
| **Member of Technical Staff** | GeeksforGeeks | Jun 2025 – Nov 2025 | Engineered scalable distributed systems using SOA, Nginx caching and RESTful APIs sustaining high-concurrency production traffic; led code reviews and authored system designs across the Code Editor infrastructure |
| **Web Developer & Technical Mentor** | Apna College | Jul 2024 – Dec 2024 | Resolved 550+ complex technical issues through systematic debugging and unit testing; mentored 5,000+ students on engineering fundamentals — 4.94/5 satisfaction rating |
| **Full Stack Developer Intern** | Navrasa Group | Aug 2024 – Sep 2024 | Shipped production-ready modular features; cut deployment cycles by 15% via optimized CI/CD and version control workflows |

---

## Projects

### [CampusHire](https://campushire-student-frontend.onrender.com) — College Placement & Job Portal `[Ongoing]`
> Next.js · Golang · Node.js · PostgreSQL · Redis · Docker · Kubernetes · n8n · AWS EC2/S3

Full-stack placement portal built for RGIPT. Role-based access (students, TPOs, admins), off-campus job aggregation from LinkedIn/Indeed/Naukri via autonomous scraping agents, alumni networking, and real-time admin analytics. Distributed microservices backend with Redis caching, JWT auth with OTP verification, and Kubernetes orchestration. Designed from scratch — architecture, database schema, infra, deployment.

**[Live →](https://campushire-student-frontend.onrender.com)**

---

### [Mail Sentinel](https://mail-sentinel.vercel.app/) — AI Email Automation System `[Mar 2025]`
> Node.js · Next.js · TypeScript · BullMQ · Redis · Groq API · Gmail API · OAuth2 · Docker

End-to-end Gmail automation: BullMQ workers poll inboxes, Groq LLaMA-3.3-70b classifies emails, applies labels, and drafts auto-replies within seconds. Built a 4-layer rate-limiting system (inbox snapshots, per-cycle caps, job staggering, concurrency control) to stay under API quotas. OAuth2 tokens scoped to minimum permissions, stored in Redis, never exposed client-side.

**[Live →](https://mail-sentinel.vercel.app/)**

---

### [Plant Disease Detection](https://github.com/niteshsaini9568/SAS-International-Hackathon) `[Oct – Nov 2024]`
> TensorFlow · Keras · CNN · Gemini API · Streamlit

Real-time plant disease detection across 38+ diseases at 92% accuracy, trained on the PlantVillage dataset. Paired the CNN with a Gemini-powered chatbot for personalized, multilingual treatment guidance — farmers upload a leaf image and get an instant diagnosis.

**[Live →](https://sas-international-hackathon.streamlit.app/)** · **[Code →](https://github.com/niteshsaini9568/SAS-International-Hackathon)**

---

### [Techmate Marketplace](https://github.com/niteshsaini9568/Techmate-Frontend) `[Nov – Dec 2024]`
> React · Node.js · MongoDB · Express · Docker · Razorpay

Scalable MERN marketplace for graphic design services and electronics, with JWT auth, Razorpay payments, Docker deployment and a CI/CD pipeline.

**[Live →](https://techmate-frontend-alpha.vercel.app/)** · **[Code →](https://github.com/niteshsaini9568/Techmate-Frontend)**

---

### [AIChE Student Platform](https://www.aichergipt.com/) `[Jun – Jul 2024]`
> React · Node.js · MongoDB · AWS EC2 · Razorpay · SEO

High-performance platform on AWS EC2 serving 2,000+ active users. SEO work drove 25% organic traffic growth and a 20% CTR lift. Owned the full deployment lifecycle from system design to production monitoring.

**[Live →](https://www.aichergipt.com/)**

---

## Stack

**Languages**

<p align="left">
  <img src="https://skillicons.dev/icons?i=ts,js,py,cpp,bash,go&theme=dark" />
</p>

**AI & LLM**

<p align="left">
  <img src="https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini-8E75F5?style=flat&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/Kimi_K2-4D6BFE?style=flat" />
  <img src="https://img.shields.io/badge/Groq-F55036?style=flat" />
  <img src="https://img.shields.io/badge/Vector_Search-4169E1?style=flat" />
  <img src="https://img.shields.io/badge/RAG_Pipelines-6E40C9?style=flat" />
</p>

**Frontend**

<p align="left">
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,html,css&theme=dark" />
</p>

**Backend & Databases**

<p align="left">
  <img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,postgres,mongodb,redis&theme=dark" />
</p>

**Infrastructure & DevOps**

<p align="left">
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,aws,nginx,githubactions,linux&theme=dark" />
</p>

**Automation & Tooling**

<p align="left">
  <img src="https://skillicons.dev/icons?i=git,github,vscode,postman,vercel,figma&theme=dark" />
  <br/>
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/BullMQ-DC382D?style=flat&logo=redis&logoColor=white" />
</p>

---

## Achievements

- **Top 5%** — Dark Patterns Buster Hackathon, IIT-BHU (1,800+ teams)
- **Top 5** — Level Supermind AI Hackathon, Mumbai
- **Runner Up** — SAS International Hackathon (plant disease detection, 38+ diseases)
- **4th of 20** — IEEE Code Current competitive programming contest
- **Speaker** — GeeksforGeeks development workshops, Bangalore HQ (200+ attendees)
- **DSA Tutor** — handpicked to mentor junior students in Data Structures & Algorithms
- **400+ problems** solved across LeetCode and GeeksforGeeks

---

## GitHub Stats

<table align="center">
  <tr>
    <td align="center" width="33%">
      <img src="https://git-hub-stats-card-generator.vercel.app/api/svg?username=niteshsaini9568&theme=dark&chart=bars" alt="GitHub Stats" />
    </td>
    <td align="center" width="33%">
      <img src="https://git-hub-stats-card-generator.vercel.app/api/svg?username=niteshsaini9568&type=languages&theme=dark&chart=bars" alt="Language Stats" />
    </td>
    <td align="center" width="33%">
      <img src="https://git-hub-stats-card-generator.vercel.app/api/svg?username=niteshsaini9568&type=contributions&theme=dark" alt="Contribution Stats" />
    </td>
  </tr>
</table>

---

## Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=niteshsaini9568&theme=github-compact&bg_color=0d1117&color=58a6ff&line=58a6ff&point=c9d1d9&area=true&hide_border=false&border_color=30363d" alt="Activity Graph" />
</p>

---

## Advanced GitHub Insights

<div align="center">
<table>
  <tr>
    <td width="50%">
      <a href="https://next.ossinsight.io/widgets/official/compose-user-dashboard-stats?user_id=139841989" target="_blank" align="center">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://next.ossinsight.io/widgets/official/compose-user-dashboard-stats/thumbnail.png?user_id=139841989&image_size=auto&color_scheme=dark" width="771" height="auto">
          <img alt="Dashboard stats of @niteshsaini9568" src="https://next.ossinsight.io/widgets/official/compose-user-dashboard-stats/thumbnail.png?user_id=139841989&image_size=auto&color_scheme=light" width="771" height="auto">
        </picture>
      </a>
    </td>
    <td width="50%">
      <a href="https://next.ossinsight.io/widgets/official/analyze-repo-pushes-and-commits-per-month?repo_id=765355456" target="_blank" align="center">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://next.ossinsight.io/widgets/official/analyze-repo-pushes-and-commits-per-month/thumbnail.png?repo_id=765355456&image_size=auto&color_scheme=dark" width="721" height="auto">
          <img alt="Pushes and Commits" src="https://next.ossinsight.io/widgets/official/analyze-repo-pushes-and-commits-per-month/thumbnail.png?repo_id=765355456&image_size=auto&color_scheme=light" width="721" height="auto">
        </picture>
      </a>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <a href="https://next.ossinsight.io/widgets/official/compose-currently-working-on?activity_type=all&user_id=139841989" target="_blank" align="center">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://next.ossinsight.io/widgets/official/compose-currently-working-on/thumbnail.png?activity_type=all&user_id=139841989&image_size=auto&color_scheme=dark" width="497.5" height="auto">
          <img alt="@niteshsaini9568's Recent Work" src="https://next.ossinsight.io/widgets/official/compose-currently-working-on/thumbnail.png?activity_type=all&user_id=139841989&image_size=auto&color_scheme=light" width="497.5" height="auto">
        </picture>
      </a>
    </td>
    <td width="50%">
      <a href="https://next.ossinsight.io/widgets/official/analyze-user-contribution-time-distribution?period=all_times&user_id=139841989" target="_blank" align="center">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://next.ossinsight.io/widgets/official/analyze-user-contribution-time-distribution/thumbnail.png?period=all_times&user_id=139841989&image_size=auto&color_scheme=dark" width="721" height="auto">
          <img alt="Contribution Time Distribution" src="https://next.ossinsight.io/widgets/official/analyze-user-contribution-time-distribution/thumbnail.png?period=all_times&user_id=139841989&image_size=auto&color_scheme=light" width="721" height="auto">
        </picture>
      </a>
    </td>
  </tr>
</table>

<a href="https://next.ossinsight.io/widgets/official/compose-activity-trends?repo_id=765355456" target="_blank" align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://next.ossinsight.io/widgets/official/compose-activity-trends/thumbnail.png?repo_id=765355456&image_size=auto&color_scheme=dark" width="815" height="auto">
    <img alt="Activity Trends" src="https://next.ossinsight.io/widgets/official/compose-activity-trends/thumbnail.png?repo_id=765355456&image_size=auto&color_scheme=light" width="815" height="auto">
  </picture>
</a>

<p><em>Advanced insights powered by <a href="https://ossinsight.io/" target="_blank">OSS Insight</a></em></p>
</div>

---

<p align="center">
  <a href="https://linkedin.com/in/nitesh-saini-b936b1257" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  &nbsp;
  <a href="https://github.com/niteshsaini9568" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  &nbsp;
  <a href="mailto:nitesh.saini.dev@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  &nbsp;
  <a href="https://portfolio-frontend-peach-one.vercel.app/" target="_blank"><img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white" /></a>
</p>
