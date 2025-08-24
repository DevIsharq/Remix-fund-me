# Remix Fund Me

A decentralized crowdfunding application built with [Remix](https://remix.ethereum.org/).

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Connect](#connect)

## Overview

Remix Fund Me is a smart contract project that allows users to create and fund campaigns on the Ethereum blockchain.

## Features

- Create fundraising campaigns
- Contribute ETH to campaigns
- Withdraw funds by campaign owner
- Transparent and decentralized

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [Remix IDE](https://remix.ethereum.org/)
- [MetaMask](https://metamask.io/) (for testing/interacting)

### Steps

1. **Clone the repository**

   ```bash
   git clone https://github.com/DevIsharq/remix-fund-me.git
   cd remix-fund-me
   ```

2. **Open Remix IDE**

   - Go to [Remix](https://remix.ethereum.org/)
   - Import the smart contract files from this repo.

3. **Compile the Contract**

   - Select the Solidity compiler.
   - Compile `FundMe.sol`.

4. **Deploy the Contract**

   - Use the "Deploy & Run Transactions" plugin.
   - Choose an environment (e.g., JavaScript VM or Injected Web3 for MetaMask).
   - Deploy the contract.

5. **Interact with the Contract**
   - Use the Remix UI to call contract functions (create campaign, fund, withdraw).

## Usage

- Create a new campaign by calling `createCampaign`.
- Fund a campaign by sending ETH to `fundCampaign`.
- Campaign owner can withdraw funds using `withdrawFunds`.

## Contributing

Pull requests are welcome. For major changes, open an issue first to discuss what you would like to change.

## License

[MIT](LICENSE)

## Connect

<p align="center">
   <a href="#" style="margin: 0 10px;">
      <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"/>
   </a>
   <a href="https://www.linkedin.com/in/ishaq-aliyu-27a388350?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3Bg7e67xyUTUy2E6nBukZAhg%3D%3D" style="margin: 0 10px;">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
   </a>
</p>
