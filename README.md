# Enoch Idowu

Computer Engineering student at **Obafemi Awolowo University** and software engineer focused on **backend systems, distributed systems, reliability and applied AI**.

I enjoy building systems that have to remain correct under real constraints, especially concurrency, payments, APIs, infrastructure and failure recovery.

[Resume](./assets/Enoch-Idowu-Resume.pdf) · [LinkedIn](https://www.linkedin.com/in/enochid/) · [Email](mailto:enochidowu@student.oauife.edu.ng)

## About

I currently work across backend engineering and product development.

At **SmartSend**, I contribute to production backend systems, APIs, messaging infrastructure, background workers, payment flows and reliability improvements.

At **Tekcify**, I build and ship software products across backend, AI and web systems. Products I have worked on have reached more than **12,000 users across 120+ countries**.

I am particularly interested in:

- Backend engineering
- Distributed systems
- Reliability and infrastructure
- Developer tools
- Payments and financial systems
- Applied AI
- Systems that need to remain correct under concurrency and failure

## Selected Engineering Projects

### [Reins](https://github.com/Enoch208/Reins)

**Runtime financial controls for teams of autonomous AI agents.**

Reins solves a concurrency problem where multiple autonomous agents can spend from the same job budget at the same time.

Instead of allowing agents to independently read a balance and make spending decisions, Reins atomically reserves budget before a payment is authorized.

```text
settled + reserved + unresolved <= approved job budget
```

Key engineering work:

- Atomic PostgreSQL reservations to prevent concurrent overspending
- Database-level enforcement of budget invariants
- Idempotent operations to prevent duplicate payments
- Reconciliation for uncertain payment outcomes
- Shared budgets across delegated and replacement agents
- Integer-based accounting for money
- Policy enforcement before authorization
- Real payment execution through OKX Agentic Wallet and X Layer
- 149 automated tests, including concurrent PostgreSQL tests

**Stack:** TypeScript, PostgreSQL, Hono, Zod, x402, OKX Agentic Wallet, X Layer

[Repository](https://github.com/Enoch208/Reins) · [Live](https://usereins.xyz)

---

### [Erilog](https://github.com/Enoch208/Erilog)

**Offline-first evidence infrastructure for physical aid distribution.**

Erilog is designed for environments where multiple field devices may record events while disconnected and later synchronize conflicting information.

The system preserves every recorded event, reconciles state deterministically and produces signed audit bundles that can be independently verified.

Key engineering work:

- Offline-first event recording with IndexedDB
- Append-only event model
- Idempotent synchronization
- Deterministic reconciliation independent of sync order
- Conflict detection between disconnected devices
- PostgreSQL-backed persistence
- SHA-256 event hashing
- Ed25519 signatures
- Signed audit bundle generation
- Independent tamper verification
- Property tests for reconciliation guarantees
- 153 automated tests

The core design principle is simple: **conflicting real-world events should never silently disappear.**

**Stack:** TypeScript, PostgreSQL, IndexedDB, Next.js, Ed25519, SHA-256, Docker

[Repository](https://github.com/Enoch208/Erilog)

---

### [Clasp](https://github.com/Enoch208/Clasp)

**Scoped and revocable wallet sessions for applications and AI agents.**

Clasp allows applications to interact with Fiber wallets without receiving permanent wallet credentials.

Applications receive limited sessions with explicit permissions, spending limits, expiration and revocation.

Key engineering work:

- 10-step authorization and policy engine
- Ed25519 signed sessions and operation requests
- Replay protection and nonce enforcement
- Atomic spend reservations
- Scoped permissions and spending limits
- Delegated permissions that can only become more restrictive
- Cascade revocation
- Keyless relay architecture
- X25519 and XChaCha20 encrypted payloads
- Real Fiber Network testnet payments
- 122 automated tests

Clasp won both its infrastructure category and the overall **Nervos Fiber Network Infrastructure Hackathon**.

**Stack:** TypeScript, Node.js, Next.js, SQLite, Ed25519, X25519, Fiber Network

[Repository](https://github.com/Enoch208/Clasp) · [Live](https://useclasp.xyz)

## More Projects

### [Parallel](https://github.com/Enoch208/parallel)

Team conference planner that uses deterministic optimization to maximize coverage across overlapping sessions.

The AI layer understands agendas and user intent, while deterministic code handles scheduling, constraints and feasibility.

**Engineering:** constraint optimization, durable workflows, transactional state changes, revision tracking, email webhooks and property testing.

### [Knot](https://github.com/Enoch208/knot)

Agent marketplace built around verifiable identity, signed quotes, bounded permissions and traceable payment lifecycles.

**Engineering:** signature verification, idempotency, state machines, content-addressed artifacts, settlement and refund paths, failure recovery and on-chain verification.

### [AlgoFlow](https://github.com/Enoch208/algoflow)

AI-assisted tool that converts natural-language algorithm descriptions into structured Mermaid flowcharts.

**Stack:** TypeScript, Next.js, Gemini, Mermaid.js

[Live](https://algoflowai.vercel.app)

## Production Engineering

Some of my strongest engineering work is in private production systems.

### SmartSend

Backend engineering for a production messaging platform.

Areas I have worked on include:

- Production APIs
- Background workers
- Messaging workflows
- Payment and subscription flows
- Media-processing pipelines
- Reliability improvements
- Production debugging and incident fixes

### Binx AI

WhatsApp-native AI assistant with voice, vision and document workflows.

I worked on backend infrastructure and AI integrations required to support real users and production traffic.

## Selected Awards

- **Winner, GTBank Squad 3.0**  
  1st place from approximately 1,600 participants

- **1st Prize, AMD AI DevMaster 2026**  
  Multimodal AI Track

- **Overall Winner, Nervos Fiber Network Infrastructure Hackathon**  
  Built Clasp, which also won its infrastructure category

- **Winner, Tezos EVM AI Hackathon 2026**  
  Built Arbiter

- **Runner-up, Zenith Bank Zecathon 5.0**  
  Selected from 449 innovators

## Technical Skills

**Languages**  
TypeScript · JavaScript · Python · Solidity · C#

**Backend**  
Node.js · Express · FastAPI · REST APIs · WebSockets · background workers

**Data**  
PostgreSQL · Redis · MongoDB · MySQL · Firebase · SQLite

**Infrastructure**  
Docker · Linux · GitHub Actions · AWS · Cloudflare · Vercel

**Frontend**  
React · Next.js · Tailwind CSS

**AI**  
LLM APIs · AI agents · retrieval systems · TensorFlow · scikit-learn

## Education

**Obafemi Awolowo University, Ile-Ife**  
Computer Engineering

## Currently Interested In

I am currently open to **software engineering internships and engineering opportunities** involving:

- Backend systems
- Distributed systems
- Infrastructure
- Reliability
- Developer tools
- Financial technology
- AI infrastructure

## Contact

- **Email:** [enochidowu@student.oauife.edu.ng](mailto:enochidowu@student.oauife.edu.ng)
- **LinkedIn:** [linkedin.com/in/enochid](https://www.linkedin.com/in/enochid/)
- **GitHub:** [github.com/Enoch208](https://github.com/Enoch208)
