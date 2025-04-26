# EVM-Wallet-Analysis-Telegram-Bot-Portfolio

A powerful Telegram bot for deep analysis of EVM-compatible wallets, uncovering trading behavior, profitability, and token deployment insights in the DeFi ecosystem.

<p align="center">
  <img src="https://github.com/stevendev0822/EVM-Wallet-Analysis-Telegram-Bot-Portfolio/blob/main/EVMWalletAnalysis.gif" alt="Main Menu">
</p>

## 🔍 Overview

This Telegram bot enables users to analyze wallet profitability, holding durations, and token deployment activity across Ethereum, Binance Smart Chain (BSC), and Base networks. It helps identify top-performing wallets, suspicious actors, and token deployers with detailed on-chain analytics, making DeFi wallet research accessible and convenient.

## ✨ Key Features

### Free Features
- **Most Profitable Wallets (1–30 days)**: Track wallets with the highest profits over a selected period, including buy amount, profit/loss, and trade count (Free: 2 wallets/day).
- **Wallet Holding Duration**: Discover how long wallets hold tokens before selling (Free: 3 wallet scans/day).
- **Most Profitable Token Deployer Wallets**: Identify wallets deploying the most profitable tokens recently, with earnings and deployment counts (Free: 2 wallets/day).

### Premium Features
- **Tokens Deployed by Wallet**: Explore all tokens deployed by a specific wallet, including token details like name, ticker, deployment date, price, market cap, and all-time high (ATH) data.
- **Unlimited Access**: Premium subscribers enjoy unlimited scans and full access to all features.

### Technical Features
- **Multi-Chain Support**: Analyze wallets and tokens across Ethereum, Binance Smart Chain, and Base networks.
- **Real-time Wallet Analysis**: Receive timely insights on wallet profitability and behavior directly in Telegram.
- **User-Friendly Interface**: Intuitive menu-driven navigation with helpful prompts and detailed reports.

## 🚀 Installation

### Prerequisites
- Python 3.8+
- Telegram Bot Token
- API credentials for blockchain data sources (e.g., Dune Analytics, Moralis)

### Setup

1. Clone the repository:

```bash
git clone https://github.com/stevendev0822/EVM-Wallet-Analysis-Telegram-Bot.git
```

2. Navigate into the project directory:

```bash
cd EVM-Wallet-Analysis-Telegram-Bot
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Create a `.env` file with your credentials (example):

```bash
# DB Configuration
MONGODB_URI="mongodb://localhost:27017/"
DB_NAME="evm_wallet_analysis"

# ZenRows API keys
ZENROWS_API_KEY=your_zenrows_api_key_here

# Moralis API keys
MORALIS_API_KEY=your_moralis_api_key_here

# Ethereum Mainnet
ETH_PROVIDER_URL=your_ethereum_rpc_endpoint
ETH_CHAIN_ID=1
ETH_ADMIN_WALLET=your_wallet_address_here

# Binance Smart Chain Mainnet
BNB_PROVIDER_URL=your_bnb_rpc_endpoint_here
BNB_CHAIN_ID=56
BNB_ADMIN_WALLET=your_wallet_address_here

# Base Mainnet
BASE_PROVIDER_URL=your_bsc_rpc_endpoint_here

# Subscription Check Interval (in seconds)
CHECK_INTERVAL=60

# TELEGRAM BOT SETTING
TELEGRAM_TOKEN=your_telegram_bot_token_here
```

5. Start the bot

```bash
python src/main.py
```

## 📱 Usage

1. Start a chat with the bot on Telegram.
2. Use the menu to select features such as "Most Profitable Wallets" or "Wallet Holding Duration."
3. Input wallet addresses or token contract addresses as prompted.
4. Receive detailed wallet analysis reports including profitability, holding times, and token deployment data.
5. Upgrade to Premium for unlimited scans and access to exclusive analytics.

## 💡 Tips for Best Results
- Use correct wallet or token contract addresses.
- Select the appropriate blockchain network (Ethereum, BSC, Base).
- Check your subscription status to access premium features.


## 🏗️ Architecture

The application follows a modular architecture:
- API layer for external data sources (primarily Dune Analytics)
- Caching system for performance optimization
- Telegram bot interface for user interaction
- Subscription management for premium features

## 💎 Subscription Model

The bot operates on a freemium model:
- **Free Tier**: Access to basic features with daily usage limits (3 token scans/day)
- **Premium Tier**: Unlimited access to all features including exclusive premium analytics

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the [MIT License](./LICENSE)

## 📞 Contact Information

- Gmail: [steven0822.dev@gmail.com](mailto:steven0822.dev@gmail.com)
- GitHub: [Steven Leal(stevendev0822)](https://github.com/stevendev0822)
- Telegram: [@stevendev0822](https://t.me/stevendev0822)
- Twitter: [@stevendev0822](https://twitter.com/stevendev0822)
- Instagram: [@stevendev0822](https://www.instagram.com/stevendev0822/)

## 🔑 Keywords
wallet analysis, DeFi, EVM, Ethereum, Binance Smart Chain, Base, Telegram bot, on-chain analytics, wallet profitability, token deployment, crypto, trading behavior, smart contracts, blockchain, crypto analysis, wallet tracking, DeFi tools, crypto investments, token analysis, crypto trading