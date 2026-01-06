# Tech Stack: AA-Enabled Multichain Wallet Dashboard

## Frontend
- **Framework:** Next.js 14 (App Router)
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **UI Components:** Shadcn/UI (based on Radix UI)
- **State Management:** Zustand (for lightweight, global wallet/app state)
- **Data Fetching:** TanStack Query (React Query)
- **Charts:** Recharts or Chart.js (for portfolio visualizations)

## Blockchain - EVM (Ethereum/Arbitrum)
- **Account Abstraction:** Safe SDK (Smart Accounts)
- **Infrastructure:** Pimlico (Bundler and Paymaster for gasless transactions)
- **Library:** Viem (for high-performance Ethereum interactions)
- **Wallet Connection:** RainbowKit + Wagmi

## Blockchain - Solana
- **Framework:** Anchor (for Rust programs)
- **Library:** @solana/web3.js & @solana/wallet-adapter-react
- **Infrastructure:** Helius (RPC & DAS API for high-speed data)

## Data & Analytics
- **Multi-Chain Portfolio:** Dune Echo API (for aggregated balances)
- **Solana Asset Data:** Helius DAS API
- **Market Data:** CoinGecko API (for live pricing and market stats)

## Development Tools
- **EVM:** Foundry (for contract development and testing)
- **Solana:** Anchor CLI & Solana CLI
- **Monorepo Management:** Turborepo (to manage frontend and contracts in one place)
- **Testing:** Playwright (E2E) & Vitest (Unit)
