<!--
Place this file in a repo named <your-username>/<your-username>
It will render on your GitHub profile.
-->

<h1 align="center">Open Source Contributor / Senior Software Engineer / Full-Stack / AI / Crypto</h1>
<p align="center">
  Team Collaboration & Contribution
</p>

<p align="center">
  <a href="mailto:seniorcoder04@gmail.com">Email</a> ·
  <!-- <a href="https://your-portfolio.com">Portfolio</a> · -->
  <!-- <a href="https://github.com/your-username">GitHub</a> -->
</p>

---

### 🚀 About
I build fast, resilient, and secure products across web, mobile, and cloud. My sweet spot:
**JS/C#/Python and a lot more** on **AWS/Azure**, with hands-on **AI/LLM** features
(RAG, embeddings, vector DBs) and **crypto/trading** integrations (multi-exchange feeds,
execution gateways, risk controls). I care about clean architecture, Core Web Vitals, and
developer ergonomics.

- 🔭 Current: Next.js + Node on AWS, RAG assistants, Stripe Billing, WebRTC
- 📈 Interests: real-time data, algorithmic trading, observability, DX tooling
- 🤝 Open to: contract/FT roles and collaborations

---

### 🧰 Toolbox
**Frontend:** React, Next.js (SSR/SSG/ISR), Angular, Vue 3, React Native, TypeScript  
**Backend:** Node.js (Fastify/NestJS/Express), PHP/Laravel, C#/.NET, Python/FastAPI  
**AI/LLM:** OpenAI/Azure OpenAI, LangChain, RAG, embeddings, Pinecone/Weaviate  
**Crypto/Trading:** Binance/Coinbase/Kraken APIs, WebSockets, order routing, Backtrader  
**Cloud & DevOps:** AWS (Lambda, API GW, S3, CloudFront, RDS/DynamoDB, SNS/SQS, Kinesis, CDK),
Azure (Functions, App Service, Service Bus, Key Vault), Docker, GitHub Actions  
**Data:** PostgreSQL/TimescaleDB, MySQL, MongoDB, Redis, GraphQL/REST, OpenAPI/Swagger  
**Practices:** event-driven, DDD/clean architecture, caching, idempotency, security by default, testing pyramid

---

### 🏗️ Featured Projects
- **Algorithmic Trading Sandbox** — Backtests → paper/live trading (Backtrader + TA-Lib).  
  _Signals → Node execution gateway (HMAC, idempotency, rate-limits); TimescaleDB storage._  
  **Repo:** `your-username/trading-sandbox` • **Tech:** Python, Node, TS, TimescaleDB, AWS

- **On-Chain Analytics Dashboard** — Wallet connect, balances, ERC-20/721 events, price overlays.  
  _SSR for shareable pages; caching & pagination; charts with live updates._  
  **Repo:** `your-username/onchain-dashboard` • **Tech:** Next.js, Node, ethers.js, Redis

- **LLM Knowledge Assistant (RAG)** — Retrieve-augmented chat for product docs.  
  _Embeddings, vector store, JSON-schema outputs, evaluation harness, safety guardrails._  
  **Repo:** `your-username/llm-rag-assistant` • **Tech:** Next.js, Node, LangChain, Pinecone

> Tip: replace the repo names above with your actual links (or set them private and add screenshots to README).

---

### 📊 Snapshot
- Core Web Vitals delivered “green” on major routes (LCP/FID/CLS)  
- p95 API latency reduced 25–40% via queueing, caching, and payload slimming  
- High-volume event systems: 5M+ events/mo @ 99.95%+ availability (DLQs, retries, idempotency)

---

### 🧪 Example Code (tiny taste)
```ts
// HMAC-signed order submit (Node + TS)
import crypto from 'crypto';
function sign(payload: string, secret: string) {
  return crypto.createHmac('sha256', secret).update(payload).digest('hex');
}
