# CryptoDevs DAO

CryptoDevs DAO is a decentralized application that allows members to propose and vote on purchasing fake NFTs. Built with Next.js and integrated with Ethereum smart contracts, this project offers a simplified interface for DAO (Decentralized Autonomous Organization) operations.

## Features

- Connect your Ethereum wallet.
- Create a proposal to purchase a fake NFT.
- Vote YAY or NAY on existing proposals.
- View a list of all proposals with their details.
- Execute a proposal after the deadline.
- (Admin only) Withdraw Ether from the DAO contract.

## Getting Started

### Prerequisites

- Node.js and npm installed.
- MetaMask or similar Ethereum wallet.

### Installation

1. Clone the repository:

   ```bash
   git clone [repository_url]
   cd [repository_directory]
   ```

2. Install the required npm packages:

   ```bash
   npm install
   ```

### Configuration

1. Add your Ethereum contract ABI and addresses in the `constants` directory.

2. Configure the frontend environment variables (if any) as per your setup.

### Running the App

1. Start the Next.js server:

   ```bash
   npm run dev
   ```

2. Open a browser and navigate to `http://localhost:3000/` to access the DAO interface.

## Usage

1. Connect your Ethereum wallet using the "Connect Wallet" button.
2. Once connected, you can create a proposal or view existing proposals.
3. Proposals can be voted on until their deadline.
4. After the voting deadline, if the proposal hasn't been executed, it can be executed based on the majority of the votes.
5. Admins have the additional capability to withdraw Ether from the DAO contract.

## Built With

- [Next.js](https://nextjs.org/)
- Ethereum Smart Contracts
- [RainbowKit](https://rainbow.me/)
- [Wagmi](#) (Ensure to provide appropriate links or references for the used tools and libraries.)
