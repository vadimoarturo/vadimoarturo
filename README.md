<div align="center">

### Senior Backend Developer · Distributed Systems · Fintech · AI Engineering

**Node.js · TypeScript · NestJS · Go · PostgreSQL · MongoDB · Redis · Kafka**

I design, build and run production backends — from architecture and implementation to reliable services operating under real-world load.

[About me](#about-me) · [Selected work](#selected-work) · [Tech stack](#tech-stack) · [How I work](#how-i-work)

</div>

---

## About me

I'm a **Senior Backend Developer** focused on production backend systems, distributed services and reliable business workflows. My work includes designing and maintaining microservices, improving critical APIs, implementing event-driven integrations and solving performance and reliability challenges.

Outside my primary role, I've built **cryptocurrency exchange and payment products** and **IVirtual**, a self-hosted AI-agent orchestration platform. Before moving into backend development, I worked extensively with **systems, networking and infrastructure**. That experience shapes how I approach deployment, observability, scaling, recovery and production support.

I work across the full engineering lifecycle: understanding the business problem, selecting an appropriate architecture, building and testing the solution, and supporting it in production.

## What I work on

| Backend & distributed systems | Fintech & crypto | AI engineering | Full-stack & operations |
| :-- | :-- | :-- | :-- |
| Microservices, REST/gRPC APIs, event-driven architecture, data integrity, async workflows | Exchange engines, market rates, payment flows, transaction lifecycles and provider integrations | Agent orchestration, LLM integrations, MCP, RAG, tool calling and human approvals | React/Next.js, Docker, CI/CD, Linux, monitoring and production debugging |

## Selected work

These are real engineering projects and case studies, rather than tutorial repositories. Some source code is intentionally private; the linked write-ups explain architecture, business workflows and my contribution without exposing commercial implementations.

<table>
<tr>
<td width="50%" valign="top">
<h3>🛒 Retail Order Fulfillment Backend</h3>
<p><strong>High-load production systems · Confidential commercial project</strong></p>
<p>Developed and launched a production backend service during a monolith-to-microservices transition, improving fulfillment workflows, idempotency and reliable event delivery. Client and operational details are intentionally anonymized.</p>
<p><strong>Focus:</strong> distributed architecture · business consistency · Kafka Outbox</p>
<a href="case-studies/retail-fulfillment.md"><strong>Read engineering case study →</strong></a>
</td>
<td width="50%" valign="top">
<h3>💱 Automated Cryptocurrency Exchange</h3>
<p><strong>End-to-end exchange lifecycle · distributed backend</strong></p>
<p>Exchange workflows for live quotes, deposit tracking, provider-side trading, payouts, fee accounting and operational recovery, supported by customer apps and an operator console.</p>
<p><strong>Focus:</strong> async execution · exchange integrations · financial state</p>
<a href="case-studies/crypto-exchange.md"><strong>Read architecture and order flow →</strong></a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>🤖 IVirtual — AI Agent Platform</h3>
<p><strong>Self-hosted orchestration · Go + React</strong></p>
<p>AI task planning and execution, multiple model providers, tool calling/MCP, document retrieval, human approval gates and recovery of interrupted workflows.</p>
<p><strong>Focus:</strong> AI orchestration · RAG/pgvector · controlled tool execution</p>
<a href="case-studies/ivirtual.md"><strong>Read technical case study →</strong></a>
</td>
<td width="50%" valign="top">
<h3>💳 Crypto Wallet &amp; Payments</h3>
<p><strong>Invoices · transaction status · web and mobile-first UX</strong></p>
<p>Cryptocurrency invoice and wallet-oriented experiences with network-specific payment details, transaction tracking, responsive applications and a Telegram Mini App.</p>
<p><strong>Focus:</strong> payment UX · external integrations · asynchronous states</p>
<a href="case-studies/crypto-payments.md"><strong>Read product case study →</strong></a>
</td>
</tr>
</table>

## Tech stack

**Backend & APIs**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white) ![REST](https://img.shields.io/badge/REST_API-555555) ![gRPC](https://img.shields.io/badge/gRPC-244C5A)

**Databases, messaging & background jobs**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white) ![Kafka](https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white) ![NATS](https://img.shields.io/badge/NATS-27AAE1) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?logo=rabbitmq&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white) ![BullMQ](https://img.shields.io/badge/BullMQ-CC3333)

**Frontend, AI & infrastructure**

![React](https://img.shields.io/badge/React-149ECA?logo=react&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black) ![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?logo=gitlab&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-222222) ![pgvector](https://img.shields.io/badge/pgvector-4169E1)

## Engineering highlights

- **Architecture and delivery:** designed and shipped a production service as part of a monolith-to-microservices migration, using NestJS/Go and sharded MongoDB.
- **Reliable order processing:** improved server-side state management and idempotency for workflows affected by unreliable connectivity and duplicate requests.
- **Event-driven consistency:** worked with gRPC and Kafka and implemented a **Transactional Outbox** for reliable business-event publication.
- **Financial integrations:** designed multi-stage exchange workflows with external liquidity providers, deposits, trades, withdrawals and explicit error/recovery states.
- **AI agents:** built a self-hosted orchestration platform with multiple LLM providers, tool/MCP integrations, document retrieval, approval steps and persistent execution.
- **Operational depth:** systems and network engineering background with Linux, Docker, VMware, Cisco, CI/CD, monitoring and troubleshooting.

## How I work

1. **Understand the business problem.** Establish constraints, current failure modes, scope and acceptance criteria.
2. **Design for maintainability.** Prefer clear service boundaries, explicit data ownership and predictable interfaces.
3. **Deliver in working increments.** Implement, test, review and document focused changes.
4. **Take responsibility for production.** Account for migrations, rollbacks, observability, security, retries and idempotency.
5. **Communicate clearly.** Explain trade-offs, progress and risks without unnecessary complexity.

I use AI-assisted coding tools when helpful, while taking personal responsibility for technical decisions, review, testing and the behavior of the final system.

## Earlier engineering experience

Before my current backend focus, I worked on infrastructure automation, Linux and Windows systems, VMware, Cisco networking and competition lab environments. This background helps me work across software and operations boundaries.

**Selected public code examples:** [Infrastructure automation](https://github.com/vadimoarturo/Autocheck-WSR-NSA) · [Vanilla JavaScript UI prototype](https://github.com/vadimoarturo/Excel-NativeJs)

---

<div align="center">

### Let's build something reliable.

Available for backend development, integrations, production troubleshooting, fintech workflows and AI engineering.

**Source availability:** Some implementations are private or employer-owned. The case studies contain sanitized, high-level technical descriptions; no credentials, proprietary code or customer data are published.

</div>
