# Plan: Core Dashboard Infrastructure & User Onboarding

## Phase 1: Project Scaffolding & Foundational Setup
- [ ] Task: Initialize Turborepo with Next.js (frontend) and Foundry (EVM contracts)
- [ ] Task: Configure Tailwind CSS and Shadcn/UI with the Grayscale/Minimalist theme
- [ ] Task: Set up the basic dashboard layout (Sidebar, Header, Main Content Area)
- [ ] Task: Conductor - User Manual Verification 'Phase 1: Project Scaffolding' (Protocol in workflow.md)

## Phase 2: User Onboarding & AA Integration
- [ ] Task: Integrate Safe SDK and a social login provider (e.g., Web3Auth) for EVM onboarding
- [ ] Task: Implement Smart Account (ERC-4337) creation and deployment on Sepolia
- [ ] Task: Set up Pimlico Bundler client for gasless account interaction
- [ ] Task: Conductor - User Manual Verification 'Phase 2: User Onboarding' (Protocol in workflow.md)

## Phase 3: Multichain Data Integration
- [ ] Task: Implement Solana wallet connection and balance fetching using @solana/web3.js
- [ ] Task: Integrate Dune Echo API to fetch unified EVM asset balances
- [ ] Task: Integrate Helius DAS API to fetch Solana asset balances and transaction metadata
- [ ] Task: Create a unified Zustand store to manage cross-chain portfolio state
- [ ] Task: Conductor - User Manual Verification 'Phase 3: Multichain Data' (Protocol in workflow.md)

## Phase 4: Dashboard Visualization
- [ ] Task: Build the Portfolio Overview component (Total Balance + Asset List)
- [ ] Task: Implement a real-time portfolio value chart using Chart.js and CoinGecko data
- [ ] Task: Add loading skeletons and error handling for all data-fetching operations
- [ ] Task: Conductor - User Manual Verification 'Phase 4: Dashboard Visualization' (Protocol in workflow.md)
