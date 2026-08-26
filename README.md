# I build AI agents that can transact on-chain.

**Full-Stack Engineer** · Yogyakarta, Indonesia · Open to remote

I work at the intersection of AI agents and on-chain execution: agents that hold a
budget, call real tools, sign real transactions, and leave an auditable trail. I ship
whole products, usually solo, usually in one to four weeks.

- 🤖 **Agent runtimes** — MCP servers, tool calling, and LLM decision layers wired to real execution
- ⛓️ **On-chain rails** — stablecoin payments, smart accounts, x402, ZK settlement
- 🚀 **Shipping** — 15 products delivered · 8× hackathon winner
- 💬 Ask me about MCP payment flows, idempotent order execution, or agent memory

### What I'm building

| Project | What it does |
|---|---|
| [**AgentPay**](https://www.agentpay.site/) | MCP-first payment runtime — autonomous agents pay in USDC across X Layer, Celo, and Arc with spend caps and audit trails |
| [**Notch3**](https://github.com/zakyirsyaad/notch3) | macOS AI assistant living in the notch — dual-wallet boundary, autonomous x402 settlement, zero-port IPC, Swift 6 |
| [**Mirai AI**](https://miraiagent.vercel.app/) | Autonomous X content agent — license-gated, OAuth 2.0 PKCE, MCP tools for Codex, Claude, and Hermes |
| [**Langclaw AI · Mantle**](https://github.com/Langclaw-AI-Mantle) | Wallet-authenticated AI research workspace with on-chain proofs — Best Deployment, Mantle Turing Test 2026 |
| [**Langclaw AI · Sui**](https://langclawsui.vercel.app/) | Sui-first AI alpha platform with encrypted verifiable memory on Walrus and Seal |
| [**Langclaw AI · Celo**](https://github.com/Langclaw-AI-Celo) | Celo-anchored AI strategy workspace with Self proof, MiniPay, and USDT usage billing |
| [**Elaina AI**](https://github.com/Elaina-AI-Agents) | AI agents reaching people through WhatsApp instead of a web chat surface |
| [**IDLE AI**](https://github.com/IDLE-AI) | AI-powered token launchpad — agent infrastructure plus a Solidity token factory and swaps |
| [**Exoduze**](https://github.com/zakyirsyaad/exoduze) | AI-agent prediction market — Next.js, Fastify, and Solana/Anchor in one monorepo |
| [**DARX**](https://darxcrypto.vercel.app/) | Crypto dark pool — encrypted orders, off-chain matching, Groth16 proof settlement on Arbitrum |
| [**wearelazydev**](https://github.com/wearelazydev) | Bounty platform where merged pull requests are proven with zkTLS — 1st place, Mammothon 2025 |
| [**Freex**](https://github.com/freexcrypto) | Rupiah-stablecoin payment gateway — non-custodial settlement split inside the same transaction |
| [**GrowFi**](https://growfi.43-134-58-217.sslip.io/) | Solana farming GameFi — Phaser 3 gameplay, marketplace, direct trades, on-chain economy |
| [**VeritasDAO**](https://github.com/veritasdao) | Web3 community crowdfunding with wallet-connected campaigns |
| [**Bekaspakai**](https://github.com/zakyirsyaad) | Second-hand marketplace built and launched solo — 1st place, Startup Hackathon ASTRO 6.0 |

### Architecture, documented

**6 shipped products · 50 architecture decision records · 1 verification script**

Six of these products carry their own architecture documentation — written the way I would
want to receive it if I joined the team tomorrow.

**Patterns applied and documented**

`layered architecture` · `ports and adapters` · `factory` · `append-only on-chain registries` ·
`off-chain compute with on-chain verification` · `two-phase settlement` · `non-custodial escrow` ·
`metered usage accounting` · `provider abstraction`

**What is inside each repository**

| File | Covers |
|---|---|
| `01-context` → `03-components` | C4 model in Mermaid — system context, containers, components |
| `04-api-surface` | Endpoints and contracts, specified in OpenAPI |
| `05-flows` | Runtime sequences for the paths that matter |
| `06-data-model` | Tables and on-chain state — which layer owns which fact |
| `07-security-model` | Trust boundaries, custody, authority, failure modes |
| `08-deployment` | Environments, networks, release path |
| `09-future-work` | What is knowingly unfinished, and why |
| `adr/0001…` | Decision records: context, decision, consequences |
| `tools/verify-docs.sh` | Checks every documented claim against the source |

**The six**

| Product | Decisions documented |
|---|---|
| [**FreexCrypto**](https://github.com/freexcrypto/Architecture-FreexCrypto) (10) | Rupiah-stablecoin settlement asset · on-chain fee split · non-custodial checkout · layered backend · three-repository split |
| [**IDLE AI**](https://github.com/IDLE-AI/Architecture-IDLE) (10) | Token-per-agent factory · fixed supply · on-chain agent metadata · wallet layer · API routes as the agent bridge |
| [**Langclaw Celo**](https://github.com/Langclaw-AI-Celo/Architecture-Langclaw-Celo) (10) | Anchoring decisions on-chain · append-only registries · metered usage vault · Ownable2Step withdrawal authority · planner over eleven providers |
| [**DARX**](https://github.com/Darx-Crypto-Dark-Pool/darx-architecture) (7) | Encrypted off-chain FIFO matching · backend proving with on-chain verification · client-signed settlement |
| [**wearelazydev**](https://github.com/wearelazydev/wearelazydev-architecture) (10) | zkTLS proof of a merged PR · on-chain bounty escrow · dedicated proof service · two-phase claim settlement |
| [**Elaina AI**](https://github.com/Elaina-AI-Agents/elaina-architecture) (3) | Agent runtime and messaging integration · C4, Mermaid, and OpenAPI as the documentation contract |

### Recent wins

- 🥇 **Best Deployment Project** — Mantle Turing Test Hackathon 2026
- 🥇 **1st Place** — Mammothon 2025 by Encode Club × Celestia Foundation
- 🥈 **2nd Place** — MetaMask Card Hackathon
- 🥈 **2nd Place** — Indonesia Hacker House Web3 Hackathon 2025 by Manta Network

### Stack

```text
AI        OpenAI · Vercel AI SDK · LangChain · MCP · RAG · tool calling
Web3      Solidity · Foundry · Wagmi · Viem · Solana/Anchor · Sui Move · x402 · ZK
Frontend  Next.js · React · TypeScript · Tailwind · Shadcn UI
Backend   Node.js · Python async · Supabase · Prisma · PostgreSQL · Redis
```

### Reach me

[Portfolio](https://zaky.asia) · [LinkedIn](https://linkedin.com/in/zakyirsyad) · [Email](mailto:zaky.irsyad@gmail.com)
