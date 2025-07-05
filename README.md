# JAglotl Warcraft Kingdom: Celestial Dominion Protocol 🌌

[![Node.js](https://img.shields.io/badge/Node.js-16.x+-green.svg)](https://nodejs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-4.5+-blue.svg)](https://www.typescriptlang.org/)
[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](#license)
[![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen.svg)]()

> *"I scattered myself across four realms not from weakness, but from love. What you reassemble may not thank you for it."*
> — Final inscription from Sigeralarlotl's Shattered Throne

## 🎭 Project Overview

**JAglotl Warcraft Kingdom** is a transcendent NFT-based cosmic warfare saga where players inherit fragments of a shattered god's consciousness to command celestial hybrid armies. This isn't just another cute creature collector - it's a **psychological evolution** from wholesome mythology into existential cosmic horror.

### What Makes This Different

- **Professional Game Engine**: Enterprise-grade TypeScript architecture
- **Psychological Transformation**: Collection experience evolves from cute to cosmic horror
- **True Utility**: Every NFT powers actual game mechanics
- **Cosmic Horror Narrative**: Lovecraftian themes through interactive storytelling
- **Blockchain Integration**: MetaMask wallet connectivity with multi-token economy

## 🚀 Quick Start

### Prerequisites

- Node.js 16.x or higher
- Git
- Visual Studio Code (recommended)
- MetaMask wallet

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/jaglotl-warcraft.git
cd jaglotl-warcraft

# Install dependencies
npm install

# Configure environment
cp .env.example .env

# Start development server
npm run dev
```

### Environment Setup

Create a `.env` file with the following variables:

```env
NODE_ENV=development
PORT=3000
MONGODB_URI=your_mongodb_connection_string
METAMASK_API_KEY=your_metamask_api_key
BLOCKCHAIN_NETWORK=polygon_testnet
JWAR_TOKEN_CONTRACT=your_token_contract_address
```

## 🏰 The Four Fractured Kingdoms

### Jaglotl Dominion (*Fortis in Aeternum*)
**The Strength Fragment** - Masters of primal power and regenerative warfare
- Primary Resource: Celestial Gold
- Special Ability: Endless Endurance
- Psychological Burden: Physical might without purpose

### Leolotl Empire (*Potestas Regalis*)
**The Authority Fragment** - Solar sovereigns wielding divine command
- Primary Resource: Divine Elixir
- Special Ability: Royal Command
- Psychological Burden: Loneliness of absolute rule

### Tigrilotl Confederation (*Ex Profundis ad Astra*)
**The Fury Fragment** - Untamed warriors of righteous wrath
- Primary Resource: Blockchain Oil
- Special Ability: Righteous Fury
- Psychological Burden: Uncontrolled rage against cosmic horrors

### Phanlotl Shadow Realm (*Ordo ex Chao*)
**The Wisdom Fragment** - Lunar mystics guarding forbidden knowledge
- Primary Resource: JWAR Tokens
- Special Ability: Forbidden Knowledge
- Psychological Burden: Terrible truths that break minds

## 🎮 Game Architecture

### Core Systems

#### BuilderManager
```typescript
const builderManager = BuilderManager.getInstance();
const buildTask = {
  type: 'CONSTRUCT',
  building: 'CelestialNexus',
  cost: {
    celestialGold: 1000,
    divineElixir: 500,
    blockchainOil: 250,
    jwarTokens: 100
  }
};
```

#### Resource Economy
- **Celestial Gold**: Primary construction currency
- **Divine Elixir**: Magical enhancement resource
- **Blockchain Oil**: Technology integration fuel
- **JWAR Tokens**: Premium speed-up and special abilities

#### Speed-Up Mechanics
| Duration | JWAR Cost | Psychological Effect |
|----------|-----------|---------------------|
| 1 Hour   | 25       | Mild divine echoes  |
| 3 Hours  | 60       | Fragmented memories |
| 1 Day    | 150      | God-consciousness bleeding |
| Instant  | 100      | Full traumatic download |

## 🧠 Gameplay Mechanics

### Memory Synthesis
Strategic battles unlock **Consciousness Echoes** - flashbacks revealing why Sigeralarlotl chose fragmentation over omnipotence.

### Psychic Archaeology
Each victory unearths deeper layers of divine trauma, forcing players to experience the cosmic horror that broke a god's mind.

### The Convergence Paradox
As players unite more fragments, they risk triggering **The Awakening** - potentially resurrecting both savior and the ancient evil he died to contain.

### Cross-Collection Metamorphosis
**Convergence Protocol Holders** become **Cosmic Inheritors**, temporarily channeling complete divine consciousness - and absolute horror.

## 💎 NFT Rarity System

### Vassals (*"Fidelis et Humilis"*)
**Memory Keepers** (Common) - Servants hiding desperate warnings in their loyalty
- Supply: 5,000
- Utility: Basic resource generation

### Champions (*"Fortis in Aeternum"*)
**Consciousness Shards** (Rare) - Warrior-memories bearing specific powers and pain
- Supply: 1,000
- Utility: Advanced building capabilities

### Sovereign Fragments (*"Potestas Regalis"*)
**Psychic Royalty** (Legendary) - Kingdom rulers embodying complete emotional states
- Supply: 200
- Utility: Kingdom-wide bonuses and special events

### The Eternal King Resurrectus (*"Rex Aeternus et Omnipotens"*)
**The Complete Horror** (Mythic) - Full restoration bringing salvation AND catastrophe
- Supply: 1
- Utility: Complete game transformation and cosmic choice

## 🏆 Achievement System

### Builder Achievements
- **Master Builder** (100 constructions): *"You build like you remember..."*
- **Speed Demon** (50 speed-ups): *"Time fractures like consciousness"*
- **Resource Baron** (1M resources spent): *"You pay the true cost now"*

### Cosmic Revelations
- **First Fragment**: *"Something stirs in the darkness..."*
- **Kingdom Unity** (25% collection): *"The memories grow stronger..."*
- **Divine Awakening** (50% collection): *"I can hear his voice..."*
- **Cosmic Horror** (75% collection): *"Now I understand why he scattered..."*
- **The Choice** (100% collection): *"The universe awaits your decision..."*

## 🔗 Blockchain Integration

### Supported Networks
- Polygon Mainnet
- Ethereum Mainnet
- Polygon Mumbai (Testnet)

### Smart Contract Features
- ERC-721 NFT standard
- Multi-token resource system
- Cross-chain compatibility
- Upgradeable contract architecture

### MetaMask Integration
```typescript
// Connect wallet
const provider = new ethers.providers.Web3Provider(window.ethereum);
await provider.send("eth_requestAccounts", []);

// Interact with game contracts
const gameContract = new ethers.Contract(contractAddress, abi, provider);
```

## 🛠️ Development

### Project Structure
```
jaglotl-warcraft/
├── src/
│   ├── contracts/          # Smart contracts
│   ├── game-engine/        # Core game logic
│   ├── builders/           # Construction system
│   ├── resources/          # Economy management
│   ├── achievements/       # Progress tracking
│   ├── nft-integration/    # Blockchain connectivity
│   └── frontend/           # User interface
├── docs/                   # Documentation
├── tests/                  # Test suites
└── scripts/                # Deployment scripts
```

### Available Scripts

```bash
# Development
npm run dev          # Start development server
npm run build        # Build for production
npm run test         # Run test suite
npm run lint         # Check code quality

# Deployment
npm run deploy:testnet    # Deploy to testnet
npm run deploy:mainnet    # Deploy to mainnet
npm run verify           # Verify contracts
```

### Testing

```bash
# Run all tests
npm test

# Run specific test suites
npm run test:builders     # Builder system tests
npm run test:resources    # Resource management tests
npm run test:nft         # NFT integration tests
npm run test:e2e         # End-to-end tests
```

## 📚 Documentation

- [Builder System Documentation](./docs/builder-system.md)
- [Resource Management Guide](./docs/resources.md)
- [NFT Integration Manual](./docs/nft-integration.md)
- [Achievement System](./docs/achievements.md)
- [Cosmic Horror Narrative](./docs/narrative.md)
- [API Reference](./docs/api.md)

## 🚦 Roadmap

### Phase 1: Foundation (Q1 2025) ✅
- [x] Core game engine development
- [x] Builder system implementation
- [x] Resource management system
- [x] Basic NFT integration

### Phase 2: Evolution (Q2 2025) 🚧
- [ ] Advanced achievement system
- [ ] Cross-collection mechanics
- [ ] AR "reality bleeding" features
- [ ] Community governance tools

### Phase 3: Revelation (Q3 2025) 📋
- [ ] Full cosmic horror narrative integration
- [ ] Convergence Protocol mechanics
- [ ] Advanced psychological gameplay
- [ ] Multi-platform deployment

### Phase 4: Transcendence (Q4 2025) 📋
- [ ] Complete ecosystem launch
- [ ] Cross-chain expansion
- [ ] Community-driven content
- [ ] Philosophical discourse platform

## 🤝 Contributing

We welcome contributors who understand the vision of creating meaningful, utility-driven NFT experiences. Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting pull requests.

### Development Setup
1. Fork the repository
2. Create a feature branch
3. Follow TypeScript best practices
4. Write comprehensive tests
5. Submit pull request with detailed description

## 🐛 Bug Reports

Please use our [Issue Template](.github/ISSUE_TEMPLATE.md) when reporting bugs. Include:
- Detailed description
- Steps to reproduce
- Expected vs actual behavior
- Screenshots/logs if applicable
- Environment details

## 📄 License & Copyright

**Proprietary Software - All Rights Reserved**

This project and all associated intellectual property, including but not limited to:
- Source code and architecture
- Game mechanics and systems
- Narrative content and mythology
- Character designs and artwork
- NFT collection concepts
- Cosmic horror elements

Are the exclusive property of:

**© 2025 VaxinX Protocol | @urlifenuggets-Regis Lara | Mr. Doppio 'Ronin' Dojo. All rights reserved.**

### Usage Restrictions
- No commercial use without explicit written permission
- No redistribution or modification of source code
- No derivative works based on game mechanics or narrative
- Educational use permitted with proper attribution
- Open source contributions welcome under project guidelines

### Contact
For licensing inquiries, partnership opportunities, or permission requests:
- Discord: @urlifenuggets
- Email: contact@vaxinx-protocol.com
- Twitter: @VaxinXProtocol

## 🌟 Acknowledgments

Special thanks to:
- The cosmic horror literary tradition that inspired our narrative depth
- The professional game development community for architectural guidance
- Early beta testers who experienced the psychological evolution firsthand
- The NFT community for demanding more meaningful utility

## ⚠️ Warning

**JAglotl Warcraft Kingdom contains mature themes including:**
- Psychological horror elements
- Existential dread and cosmic insignificance
- Divine trauma and sacrifice narratives
- Morally complex decision-making scenarios

*Not recommended for players seeking purely lighthearted entertainment.*

---

***"The parasites are still hungry. My fragments are still screaming. And you... you are still collecting."***
*— Hidden message unlocked at 100% collection completion*

---

**Built with 💜 by VaxinX Protocol|[Regis Lara] • Creator Protocol™ | 2025© Jaglotl WarCraft Kingdom
*Where Professional Development Meets Cosmic Horror*
*Where NFTs Evolve Into Philosophy*

🌌 **The universe needs new guardians. Will you choose wisdom or power?** 🌌