# Hey, I’m Will (Winoooops) 👋

[![Typing SVG](https://readme-typing-svg.demolab.com/?lines=Software+Engineer;%F0%9F%A7%A9+Agentic+AI+—+RAG%2C+LangGraph%2C+MCP;Ship+clean%2C+observable+systems)](https://git.io/typing-svg)

I’m a **Software Engineer** focusing on **Agentic AI** — LLM tools, RAG, orchestration graphs, and AI‑in‑the‑loop workflows. I build full‑stack features with **Node.js / TypeScript** and pragmatic **AWS** architectures.

---

### 📊 Stats
Stats | Langs
:--:|:--:
[![GitHub stats](https://github-readme-stats-ruddy-ten.vercel.app/api?username=winoooops&theme=gruvbox&show_icons=true&count_private=true&hide=issues,contribs)](https://github.com/winoooops) | [![Top Langs](https://github-readme-stats-ruddy-ten.vercel.app/api/top-langs/?username=winoooops&hide=Handlebars&layout=compact)](https://github.com/winoooops)

---

## 🛠 Tech Stack
<!-- Devicon: https://github.com/devicons/devicon -->
<!-- Tech Stack (grouped rows, horizontal icons) -->
<section>

  <h4>Languages</h4>
  <div style="display:flex;flex-wrap:wrap;align-items:center;gap:12px;">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript" title="TypeScript" width="36" height="36" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" title="JavaScript" width="36" height="36" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" title="Python" width="36" height="36" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" alt="C#" title="C#" width="36" height="36" />
  </div>

  <h4>Frontend</h4>
  <div style="display:flex;flex-wrap:wrap;align-items:center;gap:12px;">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React" title="React" width="36" height="36" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angular/angular-original.svg" alt="Angular" title="Angular" width="36" height="36" />
  </div>

  <h4>Backend/Fullstack</h4>
  <div style="display:flex;flex-wrap:wrap;align-items:center;gap:12px;">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js" title="Node.js" width="36" height="36" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-plain.svg" alt="NestJS" title="Next.js" width="36" height="36" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dotnetcore/dotnetcore-original.svg" alt=".NET (ASP.NET Core / EF Core)" title=".NET (ASP.NET Core / EF Core)" width="36" height="36" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" alt="FastAPI" title="FastAPI" width="36" height="36" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/graphql/graphql-plain.svg" alt="GraphQL" title="GraphQL" width="36" height="36" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" title="PostgreSQL" width="36" height="36" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" alt="MongoDB" title="MongoDB" width="36" height="36" />
  </div>

  <h4>AI & Agents</h4>
  <div style="display:flex;flex-wrap:wrap;align-items:center;gap:12px;">
    <img src="https://cdn.simpleicons.org/openai" alt="OpenAI" title="OpenAI" width="36" height="36" />
    <img src="https://cdn.simpleicons.org/langchain" alt="LangChain" title="LangChain" width="36" height="36" />
    <img src="https://cdn.simpleicons.org/anthropic" alt="Claude (Anthropic)" title="Claude" width="36" height="36" />
  </div>

  <h4>Platform & Tooling</h4>
  <div style="display:flex;flex-wrap:wrap;align-items:center;gap:12px;">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS" title="AWS" width="36" height="36" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" title="Docker" width="36" height="36" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" title="Git" width="36" height="36" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/selenium/selenium-original.svg" alt="Selenium" title="Selenium" width="36" height="36" />
  </div>
</section>

---

## 🚀 Current Side Hustles
- **Lunai** — Agentic AI Chat App *Stack:* TypeScript, Node.js, GraphQL, prompts, client/server packages.  
- **open‑swap** — Unified LLM router/proxy. *Stack:* TypeScript, provider adapters (OpenAI/Anthropic/Gemini/OpenRouter/local).  
- **chill‑mcp‑server** — Claude MCP server for global `/quote`, `/highfive`, `/chill`. *Stack:* TypeScript, shell tooling.  
- **aws‑mock‑test** — Mock‑test platform. *Stack:* React (FE), API Gateway + Lambda + DynamoDB + S3 (BE), IaC + CI.

---

## 🧪 Manifesto

```ts
// demo/generate-bio.ts
const model = new ChatOpenAI();
const prompt = ChatPromptTemplate.fromTemplate(`
[Task] Generate a concise bio (2–3 sentences) for Will.
<manifesto>
{manifesto}
</manifesto>
`);

const chain = prompt.pipe(model).pipe(new StringOutputParser());

const manifesto = `
(……)
`;

const bio = await chain.invoke({ manifesto });

/******** Response
*
* Will is a software engineer focused on **agentic AI** and **cloud‑first**, **typed** systems. He builds **RAG** pipelines and **LangGraph** orchestration with a bias toward observability and tests. He ships daily in **TypeScript/Node.js**,
* reaches for **.NET (C#)** when enterprise/runtime constraints demand it, and favors **API Gateway + Lambda + DynamoDB/S3** on AWS with OpenTelemetry/CloudWatch and CI.
* His rubric is simple: strong types, small interfaces, real telemetry, and security from day one.
********/
```
---

## 🗺️ 2025 Roadmap
- [x] Open‑source Lunai minimal agent + context router
- [ ] Publish LangGraph templates (task routing, memory, tools)
- [ ] Evals + guardrails playbook for AI features
- [ ] Ship cloud-native exam prep platform

---

## 🗣️ Say hi / AMA
- Discussions: https://github.com/winoooops/winoooops/discussions
- Issues: https://github.com/winoooops/winoooops/issues/new

---

## 📫 Connect
<a href="https://linkedin.com/in/wei-wangcspractitioner"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Wei%20Wang-blue?style=flat-square&logo=linkedin"></a>
<a href="mailto:w.wang4869@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-w.wang4869%40gmail.com-blue?style=flat-square&logo=gmail"></a>
