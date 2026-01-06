# Spec: Core Dashboard Infrastructure & User Onboarding

## Overview
This track focuses on establishing the foundational full-stack infrastructure for the AA-Enabled Multichain Wallet Dashboard. The goal is to allow a user to "connect" via a social login (leveraging Account Abstraction), generate a smart account on an EVM chain, and view their unified portfolio balances from both EVM and Solana in a clean, minimalist interface.

## User Stories
- **Onboarding:** As a newcomer, I want to create a wallet using my email so I don't have to manage a seed phrase.
- **Portfolio View:** As a user, I want to see my total balance and individual asset holdings across Ethereum/Arbitrum and Solana in one place.
- **Analytics:** As a user, I want to see a simple 24h performance chart of my total portfolio.

## Functional Requirements
- **Next.js Project Setup:** Initialize the monorepo structure with Turborepo.
- **Smart Account Integration:** Implement Safe SDK for ERC-4337 smart account creation on Sepolia (EVM testnet).
- **Solana Integration:** Connect to Solana devnet and fetch basic token balances.
- **Data Fetching:** Integrate Dune Echo API (EVM) and Helius DAS (Solana) to aggregate portfolio data.
- **UI/UX:** Build a responsive, grayscale/minimalist dashboard layout with Shadcn/UI.

## Non-Functional Requirements
- **Performance:** Initial dashboard load time < 2 seconds.
- **Security:** Social logins handled via secure providers (e.g., Web3Auth or similar integrated with Safe).
- **Test Coverage:** >80% for core logic.

## Technical Constraints
- **Chains:** Ethereum Sepolia (EVM) and Solana Devnet.
- **Tools:** Safe SDK, Pimlico (Bundler), Helius (Solana RPC/DAS), Dune API.
