# Solana Token Presale Smart Contract

This smart contract, built using the Anchor framework, facilitates the sale of SPL tokens, featuring a presale mechanism and allocation tickets.

## Contact
Telegram: @degencap777

For any inquiries regarding this repository, please reach out, and we can establish a suitable communication method.

## Key Features

- **Token Sale:** Users can purchase SPL tokens directly from the contract, acting as a vending machine.
  
- **Presale Mechanism:** A configurable presale phase grants exclusive token access for a predetermined duration prior to the public sale.

- **Allocation Tickets:** During the presale, users can acquire tickets that reserve their spots for purchasing SPL tokens.

- **Flexible Configuration:** Easily configure parameters such as presale and public sale timings, token prices, and ticket allocation limits.

## Prerequisites

Ensure you have the following tools installed:

- [Rust](https://www.rust-lang.org/tools/install)
- [Cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html)
- [Anchor CLI](https://project-serum.github.io/anchor/getting-started/installation.html)
- [Node.js](https://nodejs.org/en/download/)
- [Yarn](https://yarnpkg.com/getting-started/install)

## Getting Started

1. **Installation:** Clone the repository and install dependencies.

   ```bash
   git clone https://github.com/degencap777/Solana-presale-smart-contract.git
   cd Solana-presale-smart-contract
   yarn
   ```

2. **Build the Smart Contract:**

   ```bash
   anchor build
   ```

3. **Run Tests:**

   ```bash
   anchor test
   ```

4. **Deploy:**

   Switch to your desired network and deploy:

   ```bash
   anchor deploy
   ```