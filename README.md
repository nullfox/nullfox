### 👋 Hey, I'm Ben Fox
Full-stack engineer & entrepreneur building across four areas: **applied LLM / AI systems**, **on-chain infrastructure**, **real-time backend**, and **shipped consumer products** — in TypeScript, React Native, and GraphQL.

I've designed, built, and operated production systems solo, end to end. California-based, open to contract and full-time work.

---

### 🧩 Selected Engineering
Sanitized excerpts from private production systems — the subsystems worth reading on their own, with the domain edge stripped out.

#### 🔌 [chart-extraction-techniques](https://github.com/nullfox/chart-extraction-techniques)
Two techniques from a browser-based market-data tool, extracted and sanitized.  
Built in: TypeScript · MV3 browser extensions · applied LLM + vision extraction  
→ Reads a web app's own WebSocket feed from the main world, and pulls trustworthy structured data out of an LLM by having a deterministic solver check the model's work.

#### 💸 [aluro-selected-systems](https://github.com/nullfox/aluro-selected-systems)
Two subsystems from a merchant-of-record payments platform, extracted and sanitized.  
Built in: TypeScript · Ethereum / viem · AWS KMS · Stripe / PayPal rails  
→ Fuzzy fiat-to-invoice payment matching with transposition detection, and KMS-signed USDC settlement where the private key never leaves the HSM.

---

### ⛓️ On-Chain Infrastructure

#### ⚡ [Gambit](https://github.com/nullfox/gambit)
A low-latency EVM execution engine for time-sensitive DEX trades, built around a pluggable multi-DEX adapter layer.  
Built in: TypeScript · ethers.js · TypeChain · multi-chain (Arbitrum · BSC · Avalanche)  
→ Adapter pattern isolating per-DEX router/factory quirks, live gas estimation with block-limit clamping, fee-on-transfer support, and slippage/price-impact math.

#### 🦊 [Foxhole](https://github.com/nullfox/foxhole)
A Solana execution system with on-chain safety screening and automated position management.  
Built in: TypeScript · Solana · Raydium AMM · @solana/web3.js  
→ Composable safety-filter pipeline (mint-renounced / freeze / metadata / LP-burn / pool-size), a position manager with trailing stops and a catastrophic-loss guard, and versioned transactions with dual-path token-account detection.

---

### ⚙️ Real-Time Backend

#### 📊 [Stonks Love](https://github.com/nullfox/stonks-love)
A real-time backend fusing live market data with social sentiment, exposed through one GraphQL API. Three independent Node processes over MySQL + Redis.  
Built in: TypeScript · Apollo GraphQL · Bull / Redis · Polygon.io WebSocket · PM2  
→ Live per-minute market ingestion, a time-of-day-normalized relative-volume signal, a queue-driven scraping/backfill pipeline, and DataLoader batching throughout.

---

### 📱 Products

#### 🩺 [DBT Pal](https://www.dbtpal.app) *(live, iOS)*
A diary-card app for people practicing Dialectical Behavior Therapy — fast urge/emotion/skill logging, AI coach, weekly insights. Live on the App Store with paying subscribers; actively maintained.  
React Native · on-device storage · iCloud sync · LLM features

#### 💉 [Done Dose](https://donedose.com) *(live, iOS)*
Medication, injection, and supplement tracking. Live on iOS. React Native.

#### 🧾 PayPrompt
Shipped a QuickBooks-integrated invoice-reminder SaaS end-to-end — OAuth sync, Stripe billing, scheduled reminder workflows. Featured on Product Hunt and Hacker News.  
TypeScript · GraphQL · Prisma · Postgres · AWS SES · Next.js

---

### 🧰 Utilities & Starters
- **SoloStack** – opinionated full-stack TypeScript starter (Expo + Prisma + GraphQL Yoga)  
- **RN Vision Utils** – React Native Vision + Skia overlays and frame processors  

---

### 🧭 Now
- Building sanitized case studies of production systems → [nullfox.com](https://nullfox.com)  
- Open to contract and full-time work in applied AI, backend, and full-stack

---

### ⚙️ Stack & Tools
TypeScript · React / React Native · GraphQL (Apollo · Pothos · Yoga) · Prisma · PostgreSQL · MySQL · Redis  
AWS (Lambda, SQS, SES, RDS, ECS, KMS) · EAS / Expo · Tailwind · Next.js · Node.js · Terraform · viem / ethers · Solana · Ethereum

---

### ☕ About Me
California-based engineer with a background in startups, fintech, on-chain infrastructure, and design. I've built and operated production systems solo, end to end — comfortable both shipping polished apps and building systems that move money.  
Outside of code: motorcycles, photography, and functional design.  
Always open to collaborations or early-stage tech chats — [LinkedIn](https://www.linkedin.com/in/nullfox) • [nullfox.com](https://nullfox.com)
