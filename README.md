<div align="center">

<img src="./assets/crab-dev.svg" alt="Isometric illustration of a crab engineer at a terminal, surrounded by agent, RAG and automation pipeline nodes" width="100%" />

# Daniyal

### AI &amp; Automation Engineer · Islamabad, Pakistan

Most AI projects die between the demo and production.<br/>
I work on the part that survives that gap.

<a href="https://aideon.pages.dev/"><img src="https://img.shields.io/badge/aideon.pages.dev-1f6feb?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/muhammad-daniyal-b27884230/"><img src="https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://x.com/BrosBd"><img src="https://img.shields.io/badge/@BrosBd-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>

</div>

---

## What I do

I build LLM systems end to end — retrieval, orchestration, and the automation
infrastructure that keeps them running. A prototype that answers well on ten
handpicked questions is not a product; the work is in what happens on the
ten thousand you didn't anticipate.

<table>
<tr>
<td width="50%" valign="top">

#### 🧠 LLM &amp; agent systems

Multi-agent architectures, tool-calling loops, and model orchestration.
Prompts treated as engineering artifacts — versioned, evaluated, and
regression-tested rather than tweaked by feel.

</td>
<td width="50%" valign="top">

#### 🔍 RAG pipelines

Chunking strategy, embeddings, vector search, reranking, and grounded
generation. Retrieval quality is where most RAG systems quietly fail,
so that is where most of the effort goes.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🔄 Workflow automation

n8n pipelines wiring APIs, webhooks, LLMs, and databases into processes
that run unattended — and fail loudly rather than silently.

</td>
<td width="50%" valign="top">

#### 🗄️ Data &amp; infrastructure

Postgres and Supabase schemas, FastAPI services, Dockerized deployments,
and Cloudflare edge delivery for everything above.

</td>
</tr>
</table>

---

## Selected work

#### [LLM-Resume-Analyzer](https://github.com/mdaniyal69/LLM-Resume-Analyzer) · `Python` · `LLM APIs`

Structured extraction and role-fit scoring over unstructured resumes. Parses
free-form documents into a normalised schema, then evaluates candidates against
role requirements — turning a stack of PDFs into comparable, queryable signal.

#### Forex signal engine · `Python` · `MCP` · `PostgreSQL` <sub>private</sub>

Live OANDA market feed feeding a multi-strategy confluence scorer. Strategies
vote independently and their agreement is scored, rather than trusting any single
indicator. Exposed to AI agents through a Model Context Protocol server, so an
agent can query live market structure as a tool.

#### Proposal generation engine · `JavaScript` · `LLM APIs` <sub>private</sub>

Analyses job postings, extracts requirements, and drafts tailored proposals
grounded in a profile of real past work — cutting a repetitive writing task to
a review-and-send step.

#### n8n automation pipelines · `n8n` · `PostgreSQL` · `Webhooks` <sub>private</sub>

Production workflow automations connecting APIs, LLMs, webhooks, and databases,
with versioned workflow backups so a broken node is a rollback rather than a
rebuild.

<sub>Several projects are private — client work, or in cleanup for public release.
Happy to walk through architecture and tradeoffs on request.</sub>

---

## Toolkit

**AI &amp; LLM**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![MCP](https://img.shields.io/badge/MCP-1f6feb?style=flat-square&logo=protocolsio&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-0b3d2e?style=flat-square&logo=databricks&logoColor=white)

**Automation &amp; backend**  
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Data &amp; cloud**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

---

## How I think about this work

**Retrieval beats prompting.** A sharper prompt on the wrong context is wasted
effort. Fix what the model sees first.

**Evaluate, then iterate.** Without a measurement you are not improving a system,
you are redecorating it.

**Fail loudly.** An automation that breaks silently is worse than one that never
ran — you keep trusting output that stopped being true.

**Ship the boring plumbing.** Retries, schema validation, and backups are what
separate a demo from something people depend on.

---

## Currently

- Building agentic systems that chain LLMs, tools, and live data sources
- Going deep on retrieval quality — the part of RAG most people skip
- Exploring knowledge graphs as structured memory for agents
- Working on trading infrastructure and market data pipelines

---

<div align="center">

**Open to collaborating on AI automation and LLM product work.**

<a href="https://aideon.pages.dev/">aideon.pages.dev</a>

</div>
