# 💸 Fund It Up – Decentralized Crowdfunding & Team Building Platform on Ethereum

**"Fund It Up"** is a revolutionary **decentralized application (DApp)** built on the **Ethereum Sepolia Testnet** that transforms how startup ideas evolve into reality through blockchain technology.

> *"Empowering visionaries to fund their dreams and build world-class teams - all on-chain."*

## 🌟 What We Do

Fund It Up connects three critical elements of startup success in one decentralized platform:
- 🚀 **Launch ideas** with transparent fundraising
- 💰 **Secure community funding** through smart contracts
- 🧑‍💻 **Build talented teams** with role-specific recruiting

---

<p align="center">
  <img src="https://img.shields.io/badge/Powered_by-Ethereum-3c3c3d?style=for-the-badge&logo=ethereum" />
  <img src="https://img.shields.io/badge/Network-Sepolia_Testnet-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Made_with-Love-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Built_by-nam-blue?style=for-the-badge" />
</p>

---

## ✨ Key Features

### 🚀 Startup Launchpad
Bring your vision to life on the blockchain with our comprehensive startup submission system:
- **Detailed Profiles**: Share your startup's name, comprehensive description, mission, and vision
- **Funding Goals**: Set transparent funding targets with milestone-based unlocking
- **Roadmap Integration**: Outline your development journey for potential backers
- **Problem-Solution Format**: Clearly articulate the problem you're solving and your unique approach

### 💰 Web3 Native Fundraising
Our smart contract-based crowdfunding revolutionizes traditional investment:
- **Transparent Transactions**: All donations are immutably recorded on-chain
- **Progress Tracking**: Real-time funding dashboards for creators and supporters
- **Milestone Activation**: Funds unlock as predefined project milestones are met
- **Backer Rewards**: Token-based incentives for early supporters
- **Refund Protection**: Automatic refunds if minimum funding goals aren't reached

### 🧩 Team Building Marketplace
Find the perfect talent for your startup with our role-based posting system:
- **Specialized Roles**:
  - 💻 Frontend Developer  
  - ⚙️ Backend Developer  
  - 🤝 HR / Co-Founder  
  - 🎨 UI/UX Designer  
  - 🤖 AI/ML Engineer  
  - 📊 Data Scientist
  - 📱 Mobile Developer
  - 📈 Growth Hacker
  - 🔒 Security Engineer
  - and more!

- **Skill Matching**: AI-powered recommendation system connects founders with ideal candidates
- **On-Chain Applications**: Apply directly through blockchain-verified credentials
- **Equity Offerings**: Offer token-based compensation and equity tracking
- **Team Transparency**: Public team building progress visible to backers

### 🔐 True Decentralization & Security
We've built a platform that embraces core Web3 principles:
- **Permissionless Access**: Anyone can launch or support projects without gatekeepers
- **Censorship Resistant**: No central authority can remove legitimate projects
- **Immutable Records**: All transactions and project details are permanent on-chain
- **Community Governance**: Platform evolution guided by stakeholder voting
- **Open Source Development**: Fully transparent codebase for community audit and improvement

---

## 🔧 Tech Stack

| Layer            | Technology                                                |
|------------------|-----------------------------------------------------------|
| Smart Contracts  | Solidity, Hardhat, OpenZeppelin, Chainlink (Oracles)      |
| Frontend         | Next.js, ethers.js, Rainbow Kit, Tailwind CSS             |
| Authentication   | ENS, Sign-in with Ethereum (SIWE)                         |
| Wallet Connect   | MetaMask, WalletConnect, Coinbase Wallet                  |
| Storage          | IPFS/Filecoin via NFT.Storage                             |
| Blockchain       | Ethereum (Sepolia Testnet)                                |
| Testing          | Hardhat, Mocha, Chai                                      |
| Deployment       | Vercel, GitHub Actions                                    |

---

## 🧪 Installation & Setup

### Prerequisites
- Node.js v16+
- MetaMask browser extension
- Sepolia ETH (Get some from [Sepolia Faucet](https://sepoliafaucet.com))

### 1. Clone the Repository
```bash
git clone https://github.com/nam-team/fund-it-up.git
cd fund-it-up
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Configure Environment
Create a `.env.local` file in the root directory:
```
NEXT_PUBLIC_ALCHEMY_API_KEY=your_alchemy_key_here
NEXT_PUBLIC_CONTRACT_ADDRESS=your_deployed_contract_address
NEXT_PUBLIC_NETWORK_ID=11155111  # Sepolia Testnet
```

### 4. Deploy Smart Contracts
```bash
npx hardhat compile
npx hardhat run scripts/deploy.js --network sepolia
```
> Copy the deployed contract address to your `.env.local` file

### 5. Launch Development Server
```bash
npm run dev
```

### 6. Connect & Explore
1. Open http://localhost:3000 in your browser
2. Connect your MetaMask wallet
3. Switch to Sepolia Testnet network
4. Start exploring, funding, or creating projects!

---

## 🔄 Workflow Diagram

```
┌─────────────────┐     ┌───────────────┐     ┌─────────────────┐
│                 │     │               │     │                 │
│  Create Project │────▶│  Get Funded   │────▶│  Build Team     │
│                 │     │               │     │                 │
└─────────────────┘     └───────────────┘     └─────────────────┘
        │                      │                      │
        ▼                      ▼                      ▼
┌─────────────────┐     ┌───────────────┐     ┌─────────────────┐
│                 │     │               │     │                 │
│  IPFS Storage   │     │  Smart        │     │  Role-Based     │
│  for Details    │     │  Contracts    │     │  Recruiting     │
│                 │     │               │     │                 │
└─────────────────┘     └───────────────┘     └─────────────────┘
```


## 🛣️ Roadmap

| Phase | Timeline | Features |
|-------|----------|----------|
| Alpha | Q2 2025 | Basic project submission, funding, and role posting |
| Beta | Q3 2025 | Enhanced profiles, milestone-based funding, application system |
| v1.0 | Q4 2025 | Token rewards, governance, reputation system |
| v2.0 | Q1 2026 | Multi-chain support, DAO integration, accelerator partnerships |

## 👨‍💻 Made with ❤️ by Team nam

We are nam – passionate builders, developers, and dreamers committed to leveraging blockchain technology to transform how startups are born and nurtured.

Our mission is to democratize access to capital and talent for visionary founders worldwide. We believe that great ideas should never fail due to lack of funding or inability to find the right team members.

### Core Team
- **Vanshdeep sharma** - Smart Contract Developer,Blockchain Architect
- **Akshat,Asmi** - Frontend Engineer
- **Bhavya** - UX/UI Designer

### Connect with us
- ✉️ Email: caramelizeeed@gmail.com

## 🤝 Contributing

We welcome contributions from the community! Please check our [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

Licensed under the MIT License.

See [LICENSE](LICENSE) for full details.

---

<p align="center">
  <em>Building the future of startup creation, one block at a time.</em>
</p>
