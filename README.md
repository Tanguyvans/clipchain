# ClipChain

**Transform your ideas into viral AI-generated videos instantly within the Base App. Share your creations and climb the leaderboard as your videos get recasted across the network.**

ClipChain is a complete ecosystem featuring an XMTP AI agent and a Base mini app that makes creating and sharing AI-generated videos fun, social, and rewarding.

## Overview

ClipChain combines the power of Google's Veo 3.1 Fast AI model with Web3 social features to create a unique video generation and sharing platform. Users can generate videos through natural language prompts, pay with USDC on Base network, share their creations on Farcaster, and compete on a global leaderboard.

### Live Deployment

- **Agent Address**: `clipchain.base.eth` (Base Name)
- **ENS Name**: `clipchain.eth` (Ethereum Name Service)
- **Mini App**: [https://new-mini-app-quickstart-pi-nine.vercel.app/](https://new-mini-app-quickstart-pi-nine.vercel.app/)
- **Video Demo**: [https://youtu.be/5ep42gvNxXg](https://youtu.be/5ep42gvNxXg)
- **Status**: ✅ Live and operational

## Quick Start

1. Open Base App or any XMTP-compatible client
2. Message: `clipchain.base.eth` or add it to your group chat
3. Send: `@clipchain.base.eth + your best prompt`
4. Pay 0.001 USDC and receive your AI-generated video
5. Share the video on Farcaster with `#clipchain` and compete on the leaderboard

## Key Features

### AI Agent (XMTP)

- 🎬 **AI Video Generation**: Create videos from text prompts using Veo 3.1 Fast
- 💳 **USDC Payments**: Pay-per-video model (0.001 USDC) on Base network
- ⚡ **Real-time Processing**: Live status updates and progress tracking
- 🔗 **Direct Downloads**: Instant access to generated videos
- 🎭 **Interactive UI**: Button-based navigation and commands
- 💰 **Balance Management**: Built-in payment status and transaction history
- 👥 **Group Chat Support**: Works in any Base App group chat via XMTP

### Mini App (Base)

- 📱 **Vertical Video Feed**: TikTok-style infinite scroll feed of AI-generated videos
- 🏆 **Leaderboard**: Community rankings based on total recast count
- 🔄 **Native Farcaster Integration**: Recast and compose casts via Minikit
- 📊 **Real-time Engagement Metrics**: Live likes, recasts, and comments from Farcaster
- 🎯 **Streak Tracking**: Prototype feature for user engagement (in development)
- 🔍 **Hashtag Discovery**: All videos tagged with `#clipchain` automatically appear

## Technology Stack

### Agent Stack

- **XMTP Agent SDK**: Event-driven messaging framework
- **Google Veo 3.1 Fast**: AI video generation via Fal AI API
- **Base Network**: USDC payments and transaction handling
- **XMTP Transactions**: Real-time payment verification
- **Node.js/TypeScript**: Runtime and development
- **Railway**: Cloud hosting

### Mini App Stack

- **Next.js 15**: App Router framework
- **Tailwind CSS + shadcn/ui**: Modern styling and components
- **OnchainKit Minikit**: Farcaster integration SDK
- **Neynar API**: Farcaster data and search
- **Vercel**: Deployment platform

## How It Works

### User Journey

1. **Generate Video**: Message `clipchain.base.eth` with your video prompt
2. **Payment**: Pay 0.001 USDC (valid for 1 hour)
3. **Creation**: Agent generates video using Veo 3.1 Fast AI
4. **Delivery**: Receive direct download link in chat
5. **Share**: Post to Farcaster with `#clipchain` hashtag
6. **Compete**: Videos appear in feed, recasts count toward leaderboard ranking
7. **Discover**: Browse community videos in the mini app feed

### Interactive Interface

The agent provides intuitive button-based commands:

- **💳 Check balance** - View USDC balance and payment status
- **🏆 Leaderboard** - See top creators ranked by recasts
- **📺 Video Feed** - Browse all community-generated videos

### Example Video Prompts

```
@clipchain.base.eth A dramatic Hollywood breakup scene at dusk on a quiet suburban street
@clipchain.base.eth A futuristic city with flying cars and neon lights
@clipchain.base.eth A peaceful forest with sunlight filtering through the trees
@clipchain.base.eth A chef preparing a gourmet meal in a modern kitchen
```

## Project Structure

```
clipchain/
├── agent/          # XMTP AI agent for video generation
│   └── agent/      # Core agent implementation
└── mini-app/       # Base mini app for feed and leaderboard
```

## Bounties & Achievements

### Base

- **Mini App**: Built a fully functional video feed where users can repost their favorite videos, featuring a leaderboard powered by Neynar's API and a streak tracking page (currently in prototype)
- **AI Agent**: Deployed `clipchain.base.eth`, enabling seamless Mini App interactions (feed, leaderboard) and direct video generation through simple commands. Integrated pay-as-you-go payment system for flexible usage

### XMTP

- Agent can be called in any Base App group chat, enabling interactions through the XMTP workflow for seamless communication

### ENS

- Registered `clipchain.base.eth` ENS name for enhanced usability—users can now easily call the agent in any group chat without needing to provide an address. Leverages Base App's existing ENS infrastructure for users

## Getting Started

### Agent Setup

See [agent/agent/README.md](agent/agent/README.md) for detailed agent deployment instructions.

### Mini App Setup

See [mini-app/README.md](mini-app/README.md) for detailed mini app development and deployment instructions.

**Prerequisites:**

- Node.js 18+
- Farcaster account
- Neynar API Key (paid tier required for search functionality)
- Vercel account (for deployment)

## Repositories

- **Mini App**: [https://github.com/Tanguyvans/new-mini-app-quickstart](https://github.com/Tanguyvans/new-mini-app-quickstart)
- **Agent**: [https://github.com/Tanguyvans/ethrome-base](https://github.com/Tanguyvans/ethrome-base)

## Team

- [@maxgloesener](https://t.me/maxgloesener)
- [@Tanguyvans](https://t.me/Tanguyvans)
- [@Fral01](https://t.me/Fral01)

## Learn More

- [Base Mini Apps Documentation](https://docs.base.org/docs/mini-apps/quickstart/create-new-miniapp/)
- [OnchainKit Minikit](https://onchainkit.xyz/minikit/introduction)
- [XMTP Documentation](https://xmtp.org/docs)
- [Neynar API](https://docs.neynar.com/)
- [Farcaster Protocol](https://www.farcaster.xyz/)

## License

This project was created for ETHRome 2025 hackathon.
