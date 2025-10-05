# Frontend Setup Instructions

## Development Mode (Recommended)

```bash
cd src/blocktrace-frontend-main
npm install
npm run dev
```

Access at: http://localhost:3000

## Environment Setup

Copy the environment file:
```bash
cp .env.example .env.local
```

## Important Notes

- Use `npm run dev` for development (not `npm start`)
- `npm start` requires a production build which may have errors
- Videos are excluded - add your own background videos to `/public/assets/`