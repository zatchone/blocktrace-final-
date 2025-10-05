# 🚀 Simple Setup (Just dfx commands)

```bash
# 1. Start local ICP network
dfx start --background --clean

# 2. Deploy everything (auto-builds frontend)
dfx deploy
```

That's it! 

- Frontend will be auto-built and deployed as a canister
- Access via the frontend canister URL shown after deploy
- For development, use `npm run dev` in `src/blocktrace-frontend-main/`