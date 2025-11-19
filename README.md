An automated bot for interacting with the UPBIT Giwa Sepolia DApp on GIWA Testnet, supporting Mint NFT Only and Deploy Random Contract Only.

* **UPBIT Giwa Sepolia DApp Link:** [https://giwadapp.vercel.app](https://giwadapp.vercel.app/)

## Features

- **Multi-Wallet Support**: Manage multiple wallets simultaneously
- **Mint NFT**: automated
- **Deploy**: automated

## Prerequisites

- Node.js (v22 or higher)
- npm or yarn
- Private keys for wallets you want to use
- ETH Sepolia on GIWA Testnet

## Installation

1. Clone the repository:
```bash
git clone https://github.com/questairdrop/UPBIT-Giwa-Sepolia-DApp.git
cd UPBIT-Giwa-Sepolia-DApp
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory:
```bash
nano .env
```

4. Add your private keys to the `.env` file:
```env
PRIVATE_KEY_1=your_first_private_key_here
PRIVATE_KEY_2=your_second_private_key_here
PRIVATE_KEY_3=your_third_private_key_here
```

**Note**: Private Key must be in 64 character hex format (without 0x)

**Note**: You can add as many private keys as needed. Use the format `PRIVATE_KEY_X` where X is a number.

## Usage

Run the bot:
```bash
node giwaBot.js
```

## License

This project is open source and available under the MIT License.

## Disclaimer

This bot is provided as-is for educational and automation purposes. Use at your own risk. Always verify transactions and understand the protocols you're interacting with. The authors are not responsible for any losses incurred through the use of this bot.
