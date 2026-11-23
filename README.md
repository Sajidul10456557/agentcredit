# AgentCredit

Sybil-Proof Verified Credit / Grant dApp for the BNB Chain & Binance Wallet Agent ID Hackathon.

Each person can hold only one non-transferable Agent ID (name.ai). AgentCredit checks that the connected wallet holds an Agent ID and lets it claim a one-time verified credit/grant. Duplicate claims are blocked on-chain.

This is NOT an investment. It offers no income or financial return.

## Network and contracts (BNB Smart Chain Mainnet, Chain ID 56)
- AgentCredit contract: `0x461933673C2802489d5Dc9372619C7a203C7411E`
- Agent ID (ERC-721): `0x60B9262456dE011F7d15a54CdD8c48bAaa8B022F`

## Files
- `contracts/AgentCredit.sol` - Solidity smart contract (owner permissions documented in comments)
- `index.html` - single-file frontend (plain HTML, CSS, JavaScript)

## Features
- Wallet connect (Binance Wallet / MetaMask) with Chain ID 56 check
- Agent ID check and one-time claim (real BNB for gas)
- Demo Mode (simulated flow, no gas) for judges
- Copyable read-only prompt for Binance AI Pro / Agentic Wallet (no auto-signing; the user always confirms manually)

## Owner permissions
The owner can change the grant amount, pause claims, withdraw unused BNB and transfer ownership. The owner cannot claim for others or edit who has claimed.

## Disclaimer
Hackathon project, not audited. Real BNB is used for gas on mainnet. Use at your own risk.
