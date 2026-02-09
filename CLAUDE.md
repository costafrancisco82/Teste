# Project: Teste

## Overview
Next.js web application.

## Tech Stack
- **Framework**: Next.js (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS v4
- **Package Manager**: npm

## Commands
- `npm run dev` — Start development server
- `npm run build` — Build for production
- `npm run lint` — Run linter

## Code Style
- Use TypeScript strict mode
- Prefer functional components with hooks
- Use named exports over default exports
- Follow Next.js App Router conventions (`app/` directory)

## Project Structure
```
src/
  app/          — Routes and layouts (App Router)
  components/   — Reusable UI components
  lib/          — Utility functions and shared logic
public/         — Static assets
```

## Guidelines
- Keep components small and focused
- Colocate related files (component, styles, tests)
- Use server components by default; add "use client" only when needed
- Handle errors with error boundaries and error.tsx files
