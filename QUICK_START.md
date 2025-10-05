# 🚀 Quick Start Guide

## One-Command Setup

```bash
# Install all dependencies, start dfx, and deploy
npm run setup
```

## Manual Steps (Alternative)

```bash
# 1. Install dependencies
npm install

# 2. Start local ICP network
dfx start --background --clean

# 3. Deploy canisters
dfx deploy

# 4. Start frontend
npm run dev
```

## Access Application

- **Frontend**: http://localhost:3000
- **Backend Canister**: Check `dfx canister id blocktrace_backend`

## Available Scripts

- `npm run setup` - Complete setup (install + dfx start + deploy)
- `npm run dev` - Start frontend development server
- `npm run deploy` - Deploy canisters only
- `npm run local-start` - Start dfx network only

That's it! 🎉