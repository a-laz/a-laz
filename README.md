<h1 align="center">
  Hey, I'm Alex <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30" />
</h1>

<p align="center">
  <strong>Co-founder and protocol lead at Bluecore Studios and Refi Technologies. I build compliance infrastructure for agentic finance and tokenized credit, and I publish the receipts.</strong>
</p>

<p align="center">
  <a href="mailto:alex@refi2.com">
    <img alt="Email - alex@refi2.com" src="https://img.shields.io/badge/Email-alex%40refi2.com-orange?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/alex-lazarev-48b47614b/">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Alex%20Lazarev-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

<p align="center">
  <img alt="Ethereum Standards" src="https://img.shields.io/badge/Ethereum_Standards_(ERC--8226)-111827?style=flat-square" />
  <img alt="Agentic Payments" src="https://img.shields.io/badge/Agentic_Payments_&_Spend_Mandates-111827?style=flat-square" />
  <img alt="RWA Tokenization" src="https://img.shields.io/badge/RWA_Tokenization-111827?style=flat-square" />
  <img alt="Rust & Anchor" src="https://img.shields.io/badge/Rust_&_Anchor_(Solana)-111827?style=flat-square" />
  <img alt="Solidity & Foundry" src="https://img.shields.io/badge/Solidity_&_Foundry-111827?style=flat-square" />
  <img alt="Full Stack Web" src="https://img.shields.io/badge/Full_Stack_Web-111827?style=flat-square" />
</p>

---

## 🧭 About & Focus

- 🛡 **Compliance infrastructure for agents** — mandate standards, reason codes, and asset-enforced guardrails so autonomous agents can transact on regulated assets.
- 🌱 **RWA tokenization** — Canadian second-lien mortgage credit on Solana, with on-chain transparency as the design constraint.
- 💸 **Stablecoin rails** — dollar savings on M-Pesa in Kenya, under the CBK's new VASP framework.
- 🏛 **Federal software** — Kota Foundry builds product-grade prototypes for defense workflows, currently predictive maintenance.
- 🔍 **Security research** — Immunefi and Code4rena background; every protocol claim ships with a verification path.
- 🧠 **Multi-agent systems** — LLM pipelines that research, execute, and report, with humans holding the mandate.
- ⚙️ **Ops automation** — a decade of turning manual, error-prone workflows into observable systems that run in production.

---

## 🚀 What I'm building now

<table>
  <tr>
    <td width="33%" valign="top">

<h3>🛡 ERC-8226 & Spend Mandates</h3>

**First external integration** of the Regulated Agent Mandate Standard, live on Sepolia against the reference registry:

- RAMS-aware ERC-20 with a three-layer authorization gate
- Co-designed the `ExecutionReason` interface going into the spec
- Full review published to the authors, findings on the <a href="https://ethereum-magicians.org/t/erc-8226-regulated-agent-mandate/28208">Magicians thread</a>

<sub><strong>Also:</strong> co-author of a draft EIP on asset-enforced spend mandates, grown out of Verified Agent Rails (ETHGlobal NY 2026).</sub>

</td>
    <td width="33%" valign="top">

<h3>🌱 REFI2 Protocol</h3>

Tokenization protocol for **Canadian second-lien residential mortgage credit** on Solana:

- Token-2022 with transfer-hook compliance
- PDA-controlled program architecture
- Digital twin of the mortgage book for on-chain transparency

<sub><strong>Status:</strong> pre-mainnet, pre-audit, and it says so out loud until both change. <strong>Stack:</strong> Rust, Anchor, Token-2022, Next.js.</sub>

</td>
    <td width="33%" valign="top">

<h3>📱 Mimi</h3>

**Custodial stablecoin savings wallet** for Kenya, built with local partners:

- Dollar savings in stablecoins, no crypto knowledge needed
- M-Pesa STK Push on and off ramps
- Built under the CBK's VASP Regulations (gazetted July 2026)

<sub><strong>Goal:</strong> make dollar savings as easy as sending airtime. <strong>Stack:</strong> stablecoin rails + M-Pesa integration.</sub>

</td>
  </tr>
  <tr>
    <td width="50%" valign="top" colspan="2">

<h3>🧠 Psyche</h3>

Fairloom's **agentic framework**, documented and packaged for developer adoption:

- Multi-agent workflows with planning, tool use, and evaluation
- Built from the systems running our own research and ops pipelines

</td>
    <td width="50%" valign="top">

<h3>🏛 Kota Foundry</h3>

**Federal contracting and product engineering** entity, SAM.gov registered:

- COG-M: predictive maintenance prototype for defense propulsion systems, demo-ready
- Built with a propulsion SME partner

</td>
  </tr>
</table>

### Verify it yourself

All three ERC-8226 integration contracts are source-verified on Ethereum Sepolia:

| Contract | Address |
|---|---|
| `GatedUSDRams` (RAMS-aware ERC-20) | `0xd501D68214503Fa03B5179F556029CD15D7f7cAa` |
| `VARComplianceProviderAdapter` | `0x7302C8ee3E3f53cD85E0BAF1bDe8479DD19575EB` |
| `DelegationMirror` | `0x415e267C3C2B1835667b4aDda731599a4B847A3b` |

---

## 🧰 Tech & Tools

### 🧩 Core stack

<p align="left">
  <a href="https://skillicons.dev">
    <img
      src="https://skillicons.dev/icons?i=rust,go,solidity,python,ruby,django,rails,fastapi,react,nextjs,postgresql,redis,kafka,aws,azure,docker,git,github,linux,solana&perline=10"
      alt="Tech stack icons"
    />
  </a>
</p>

- **Smart contracts:** Rust + **Anchor** (Solana, Token-2022, PDA architecture), **Solidity + Foundry** (Ethereum, fork testing against live deployments).
- **Backends:** Python, Django, DRF, FastAPI, **Go**, **Ruby on Rails**.
- **Frontends:** React, Next.js, **Turbo Rails** for HTML-first interactivity.
- **Data & async:** Postgres, **Redis**, **Kafka**, Celery.

### 🏗 Systems & infra

- gRPC / REST microservices
- Event-driven architecture (Kafka, queues, background workers)
- Dockerized services, GitHub Actions CI/CD
- AWS / Azure / **Oracle Cloud (OCI)** for deployment, storage, and queues
- Observability baked in: if it isn't measured, it didn't happen

### 📊 Protocol & AI

- ERC-8226 / RAMS integration patterns, reason-code interfaces, compliance providers
- On-chain verification tooling: pinned `cast` reads, bytecode diffing, fork test suites
- LLM multi-agent systems (tool use, planning, evaluation, orchestration)
- DeFi APIs and on-chain data pipelines

---

## 📜 Background

Smart contract security research via Immunefi and Code4rena. Before crypto: a decade operating last-mile logistics at around $100M in annual inventory, and a top-200 App Store consumer app exit (Covet). The common thread is turning messy domains (finance, logistics, trading) into clean abstractions that survive production.

---

## 📈 GitHub at a glance

<p align="center">
  <a href="https://github.com/a-laz">
    <img
      src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=a-laz&theme=github_dark"
      alt="GitHub summary stats"
    />
  </a>
</p>

<p align="center">
  <a href="https://github.com/a-laz">
    <img
      src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=a-laz&theme=github_dark"
      alt="Top languages by repo"
    />
  </a>
</p>

---

## 📫 Find me online

- ✉️ `alex@refi2.com`
- 💼 [LinkedIn](https://www.linkedin.com/in/alex-lazarev-48b47614b/)
- 🧙 [Ethereum Magicians](https://ethereum-magicians.org/u/a-laz)

<p align="center">
  <em>Every claim above points to an address, a transaction, or a thread. Reach out if you want to build something verifiable.</em>
</p>
