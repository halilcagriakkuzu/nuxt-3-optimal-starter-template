# Nuxt 3 Optimal Starter Template
Nuxt 3 starter template with most used tools

- Typescript
- ESLint
  - @typescript-eslint
- Prettier
  - @trivago/prettier-plugin-sort-imports
  - prettier-plugin-organize-attributes
  - prettier-plugin-tailwindcss
- Husky
  - Configured pre-commit to lint-staged 
  - Configured commit-msg to commitlint
- Vitest
  - @nuxt/test-utils
- Tailwind

## Setup

_Optional: use pnpm_ `https://pnpm.io/installation`

Make sure to install the dependencies:

```bash
# pnpm
pnpm install
pnpm postInstall

# to install husky hooks
pnpm prepare
```

## Development Server

Start the development server on http://localhost:3000

```bash
pnpm dev
```

## Test
To run tests:

```bash
pnpm test
```

## Production

Build the application for production:

```bash
pnpm build
```

Locally preview production build:

```bash
pnpm preview
```