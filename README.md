<img src="banner.png" alt="Ali Raza - Senior AI Engineer" width="100%" />

<p align="center">
  <b>
  <a href="https://ali-raza-ten.vercel.app">PORTFOLIO</a> &nbsp;&#8226;&nbsp;
  <a href="https://linkedin.com/in/thealirazadev">LINKEDIN</a> &nbsp;&#8226;&nbsp;
  <a href="mailto:thealirazadev@gmail.com">EMAIL</a> &nbsp;&#8226;&nbsp;
  <a href="https://github.com/thealirazadev?tab=repositories">REPOSITORIES</a>
  </b>
</p>

## About

I am a Senior AI Engineer with 7+ years in production software. I build LLM systems for production: RAG with cited answers, multi-provider LLM APIs, and workflows with human review of model output. I treat the model as one part of a reliable system, with schema-validated LLM output, cost tracking, and eval suites in CI.

- AI open source: [shopwright](https://github.com/thealirazadev/shopwright) (Claude support agent for Shopify stores), [llm-gateway](https://github.com/thealirazadev/llm-gateway) (multi-provider failover, race-safe budgets, cost tracking), [mcp-store-tools](https://github.com/thealirazadev/mcp-store-tools) (MCP server for Shopify), [rag-eval-bench](https://github.com/thealirazadev/rag-eval-bench) (retrieval benchmarking), [agent-trace-viewer](https://github.com/thealirazadev/agent-trace-viewer) (agent trace reports), [evalkit](https://github.com/thealirazadev/evalkit) (prompt and agent regression testing), [ticket-triage](https://github.com/thealirazadev/ticket-triage) (LLM triage with an eval harness), [askdocs](https://github.com/thealirazadev/askdocs) (RAG with citations), [stakelens](https://github.com/thealirazadev/stakelens) (Claude tool-use assistant over indexed on-chain data).
- Stack: Python, FastAPI, Claude, OpenAI, Gemini, MCP, PostgreSQL, pgvector, ChromaDB, Redis, Docker.
- Background: 5 years of backend and full-stack work (Laravel, WordPress, Shopify) for clients in the US, UK and EU.
- Author and maintainer of open source projects across AI, Laravel, WordPress, Shopify, and Next.js.
- Based in Lahore, Pakistan and open to remote work.

## Tech Stack

<img src="stack.png" alt="Tech stack: Python, FastAPI, PHP, Laravel, OpenAI, TypeScript, JavaScript, React, Next.js, Tailwind, WordPress, WooCommerce, Shopify, PostgreSQL, MySQL, Redis, Docker" width="100%" />

## Featured Projects

**[shopwright](https://github.com/thealirazadev/shopwright)** &nbsp;&#183;&nbsp; *Python, FastAPI, Claude, pgvector*  
AI support agent for Shopify stores: hybrid RAG with citations, tool use with customer verification,
refunds and cancellations only as proposals a merchant approves, Postgres row-level security per
store, an eval suite in CI, an embeddable widget, and a merchant dashboard.

**[llm-gateway](https://github.com/thealirazadev/llm-gateway)** &nbsp;&#183;&nbsp; *Python, FastAPI*  
OpenAI-compatible gateway in front of OpenAI, Anthropic, and Gemini, with priority failover that
never double-bills and per-key budgets that hold under concurrent traffic.

**[stakelens](https://github.com/thealirazadev/stakelens)** &nbsp;&#183;&nbsp; *Python, FastAPI, Solidity*  
Reorg-safe staking indexer with a Claude assistant that answers only through five read-only tools,
so every figure it quotes comes from SQL, not the model.

**[mcp-store-tools](https://github.com/thealirazadev/mcp-store-tools)** &nbsp;&#183;&nbsp; *Python, MCP*  
MCP server that lets Claude answer from a Shopify store's live catalog and policies. Read-only by
credential, with store text treated as untrusted input.

**[rag-eval-bench](https://github.com/thealirazadev/rag-eval-bench)** &nbsp;&#183;&nbsp; *Python*  
Measures retrieval before you tune prompts: chunking strategies and BM25, dense, and hybrid
retrievers compared on recall@k, MRR, and nDCG.

**[agent-trace-viewer](https://github.com/thealirazadev/agent-trace-viewer)** &nbsp;&#183;&nbsp; *Python*  
Turns agent traces into a per-run summary and a self-contained HTML waterfall of every model and
tool call, with latency, tokens, cost, and failures.

**[evalkit](https://github.com/thealirazadev/evalkit)** &nbsp;&#183;&nbsp; *Python*  
CLI for prompt and agent regression testing: deterministic assertions, tool-call assertions, and
LLM as judge scoring.

**[ticket-triage](https://github.com/thealirazadev/ticket-triage)** &nbsp;&#183;&nbsp; *Python, FastAPI*  
Triages support tickets with an LLM, with rule based routing, a labeled evaluation harness, and CI
accuracy gating.

**[hook-relay](https://github.com/thealirazadev/hook-relay)** &nbsp;&#183;&nbsp; *Laravel*  
Inbound webhook gateway with per-provider signature verification, at least once delivery, a dead
letter queue, and replay.

**[bookline](https://github.com/thealirazadev/bookline)** &nbsp;&#183;&nbsp; *Next.js, TypeScript*  
Appointment booking with timezone and DST correct slots, and database level double booking
prevention.

**[pulse-analytics](https://github.com/thealirazadev/pulse-analytics)** &nbsp;&#183;&nbsp; *Next.js, TypeScript*  
Privacy first, cookieless web analytics with rollup aggregation, goals, and a dashboard.

Each of these has real tests and passing CI.

## Get in touch

I am open to senior AI engineering roles (voice agents, multi-agent systems, RAG, and evals), remote, contract or full time.

- Portfolio: https://ali-raza-ten.vercel.app
- LinkedIn: https://linkedin.com/in/thealirazadev
- Email: thealirazadev@gmail.com
