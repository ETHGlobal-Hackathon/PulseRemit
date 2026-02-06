# 🌐 PulseRemit: AI-Powered Remittance Hub

PulseRemit is a next-generation, agentic remittance platform designed to automate global wealth movements. Leveraging autonomous AI agents, PulseRemit eliminates the friction of cross-border transfers while providing institutional-grade volatility protection.

## ✨ Key Features

- **🤖 Guardian Agents**: Deploy autonomous agents to handle repetitive transfers, scheduled payments, and complex financial logic via natural language.
- **🛡️ Volatility Shield**: Built-in intelligent hedging that detects currency devaluation in emerging markets and preserves value automatically.
- **🛰️ Global Connectivity**: Live tracking of wealth corridors (e.g., USA → NGN) with optimized routing via LI.FI and Circle Arc.
- **💎 Premium UX**: High-contrast, futuristic design inspired by modern fintech leaders, fully responsive for web and mobile.
- **🔗 ENS First**: Human-readable identities. No more copying long hex addresses; send wealth to `name.ens`.

## 🛠️ Technology Stack

- **Frontend**: Next.js 15 (App Router), React 19, Tailwind CSS 4.0
- **AI Engine**: Gemini 1.5 Flash (via Google Generative AI SDK)
- **Web3**: RainbowKit, Wagmi, Viem (EVM compatible)
- **Animations**: Framer Motion, Three.js (React Three Fiber)
- **Charts**: Recharts

## 🚀 Getting Started

1. **Clone the repo:**
   ```bash
   git clone https://github.com/ETHGlobal-Hackathon/PulseRemit.git
   ```

2. **Install dependencies:**
   ```bash
   npm install --legacy-peer-deps
   ```

3. **Configure Environment:**
   Copy `.env.example` to `.env.local` and add your `NEXT_PUBLIC_GEMINI_API_KEY`.

4. **Run Dev Mode:**
   ```bash
   npm run dev
   ```

## 🧑‍💻 For Developers

### Smart Contracts
PulseRemit is designed to interface with:
- **ERC-20**: Primary focus on USDC/EURC stablecoins.
- **LI.FI**: Multichain bridging and swapping logic.
- **ENS**: Resolution of user identities.

### Project Structure
- `src/services/ai.ts`: The logic-parsing engine for agent configuration.
- `src/components/shared`: Reusable high-fidelity UI components.
- `src/app/dashboard`: Integrated hub flows (Agents, History, Analytics, Flows).

## 📄 License
MIT
