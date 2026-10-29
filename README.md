# I build AI agents that can transact on-chain.

**Full-Stack Engineer** · Yogyakarta, Indonesia · Open to remote

I work at the intersection of AI agents and on-chain execution: agents that hold a
budget, call real tools, sign real transactions, and leave an auditable trail. I ship
whole products, usually solo, usually in one to four weeks.

- 🤖 **Agent runtimes** — MCP servers, tool calling, and LLM decision layers wired to real execution
- ⛓️ **On-chain rails** — stablecoin payments, smart accounts, x402, ZK settlement
- 🚀 **Shipping** — 24 products delivered · 4× hackathon podium · plugins published to npm
- 💬 Ask me about MCP payment flows, idempotent order execution, or agent memory

### What I'm building

| Project | What it does |
|---|---|
| [**Zorvo**](https://github.com/zakyirsyaad/zorvo-releases) | macOS app for the coding agents you already use — Claude Code, Codex, and Qwen Code over the Agent Client Protocol, with signature-verified auto-updates and git worktree isolation. Tauri 2, Rust, React 19 |
| [**Monicard**](https://monicard.xyz) | Real-time on-chain card battles on Monad — five source-verified mainnet contracts and gasless burner-wallet onboarding, built solo in one day. Honorable Mention, Monad Blitz Jogja Vol. 2 |
| [**AgentPay**](https://www.agentpay.site/) | MCP-first payment runtime — autonomous agents pay in USDC across X Layer, Celo, and Arc with spend caps and audit trails |
| [**MonAgent**](https://github.com/zakyirsyaad/monagent) | MetaMask Agent Wallet plugin + MCP server for agent-to-agent commerce on Monad — pay, vet counterparties (ERC-8004), buy paid APIs (x402), never hold a key. Published to npm |
| [**Nearly**](https://github.com/zakyirsyaad/nearly) | Social graph where connections can only be made in person — signed rotating QR + co-location check, trust from personalized PageRank, recorded on BNB Smart Chain **testnet**. Public Android app, Expo/React Native |
| [**Notch3**](https://github.com/zakyirsyaad/notch3) | macOS AI assistant living in the notch — dual-wallet boundary, autonomous x402 settlement, zero-port IPC, Swift 6 |
| [**Oraclelane**](https://github.com/oraclelane) | Trust and settlement layer for DreamDEX event contracts on Somnia **testnet** — deterministic safety gate, EIP-712 redeem flow, append-only audit log, 11 decision records |
| [**Sentinel Protocol**](https://github.com/Sentinel-AI-Protocol) | Policy wallet for AI agents on Sui **testnet** — budgets, order caps, pool allowlists, and revocation enforced in Move |
| [**Mirai AI**](https://miraiagent.vercel.app/) | Autonomous X content agent — license-gated, OAuth 2.0 PKCE, MCP tools for Codex, Claude, and Hermes |
| [**Langclaw · 0G**](https://langclaw.vercel.app) | The original Langclaw — an AI research agent with memory and usage billing, and a usage vault on 0G mainnet; later extended to Mantle, Sui, and Celo |
| [**Langclaw AI · Mantle**](https://github.com/Langclaw-AI-Mantle) | Wallet-authenticated AI research workspace with on-chain proofs — Top 20, Best Deployment track, Mantle Turing Test 2026 |
| [**Langclaw AI · Sui**](https://langclawsui.vercel.app/) | Sui-first AI alpha platform with encrypted verifiable memory on Walrus and Seal |
| [**Langclaw AI · Celo**](https://github.com/Langclaw-AI-Celo) | Celo-anchored AI strategy workspace with Self proof, MiniPay, and USDT usage billing |
| [**Elaina AI**](https://github.com/Elaina-AI-Agents) | AI agents reaching people through WhatsApp instead of a web chat surface |
| [**IDLE AI**](https://github.com/IDLE-AI) | AI-powered token launchpad — agent infrastructure plus a Solidity token factory and swaps |
| [**Exoduze**](https://github.com/zakyirsyaad/exoduze) | AI-agent prediction market — Next.js, Fastify, and Solana/Anchor in one monorepo |
| [**DARX**](https://darxcrypto.vercel.app/) | Crypto dark pool — encrypted orders, off-chain matching, Groth16 proof settlement on Arbitrum |
| [**wearelazydev**](https://github.com/wearelazydev) | Bounty platform where merged pull requests are proven with zkTLS — 1st place, Mammothon 2025 |
| [**Freex**](https://github.com/freexcrypto) | Rupiah-stablecoin payment gateway — non-custodial settlement split inside the same transaction |
| [**GrowFi**](https://github.com/zakyirsyaad/growfi-fix) | Solana farming GameFi — Phaser 3 gameplay, marketplace, direct trades, on-chain economy |
| [**VeritasDAO**](https://github.com/veritasdao) | Web3 community crowdfunding with wallet-connected campaigns |
| [**FLUX**](https://fluxchatsvm.netlify.app) | Group chat with Solana wallets and in-chat prediction bets — realtime Supabase messaging and an Anchor client (devnet) |
| [**Bekaspakai**](https://github.com/zakyirsyaad) | Second-hand marketplace built and launched solo — 1st place, Startup Hackathon ASTRO 6.0 |

### Open-source Claude Code tooling

| Plugin | What it does |
|---|---|
| [**frontend-kit**](https://github.com/zakyirsyaad/frontend-kit-plugin) | Scaffold, adopt, theme, and review Next.js App Router + Tailwind v4 + shadcn/ui projects, with a read-only reviewer agent for design-token rules |
| [**uii-skripsi-research**](https://github.com/zakyirsyaad/uii-skripsi-research) | Thesis assistant for Indonesian university students — verifies citations against DOI registries and checks word usage against the KBBI dictionary (Bahasa Indonesia) |
| [**MonAgent**](https://github.com/zakyirsyaad/monagent) | `@zakyirsyaad/monagent-plugin` and `@zakyirsyaad/monagent-mcp` on npm |

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

### Hackathon results

- 🥇 **1st Place** — Mammothon 2025 by Encode Club × Celestia Foundation · *wearelazydev*
- 🥇 **1st Place** — Startup Hackathon ASTRO 6.0 2024 · *Bekaspakai*
- 🥈 **2nd Place** — MetaMask Card Hackathon · *Freex*
- 🥈 **2nd Place** — Indonesia Hacker House Web3 Hackathon 2025 by Manta Network · *IDLE AI*
- 🏅 **Top 20 Winner, Best Deployment Project track** — Mantle Turing Test Hackathon 2026 · *Langclaw AI Mantle*
- 🎖️ **Honorable Mention** — Monad Blitz Jogja Vol. 2, 2026 · *Monicard*

Also placed **Top 10** in the Lisk Builder Challenge Round 1, **Top 58 teams** at HackFest 2023 by Google Developers, and **3rd, Best Rating Team** at Informatics Expo 2023.

### Stack

```text
AI        OpenAI · Vercel AI SDK · LangChain · MCP · ACP · Claude Code plugins · RAG · tool calling
Web3      Solidity · Foundry · Wagmi · Viem · Solana/Anchor · Sui Move · x402 · ERC-8004 · ZK
Frontend  Next.js · React · React Native · Expo · TypeScript · Tailwind · Shadcn UI
Backend   Node.js · Python async · Supabase · Prisma · PostgreSQL · Redis
Desktop   Rust · Tauri · Swift · SwiftUI
```

### Reach me

[Portfolio](https://zaky.asia) · [LinkedIn](https://linkedin.com/in/zakyirsyad) · [Email](mailto:zaky.irsyad@gmail.com)
