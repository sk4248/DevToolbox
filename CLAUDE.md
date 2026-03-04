# DevToolbox

A developer utilities web app built with React, TypeScript, and Vite

## Stack
- React 18 + Typescript
- Vite for bundling
- Yarn for package management
- CSS Modules for styling (no Tailwind)

## Commands

- `yarn dev` - start dev server
- `yarn build` - production build
- `yarn lint` - run ESLint
- `yarn test` - run tests with Vitest

## Code Conventions 

- Functional components only, no class components
- Named exports, no default exports (except pages)
- Use `interface` over `type` for object shapes
- File naming: PascalCase for components (`JsonFormatter.tsx`), camelCase for utilities (`formatJson.ts`)
- One component per file
- Colocate tests next ro source files (`Button.tsx` -> `Button.test.tsx`)
- Prefer early returns over nested conditionals
- No semicolons
- Single quptes for strings

  ## Project Structure

  src/
    components/    # Shared UI components (Button, Card, Layout)
    tools/         # Each tool gets its own folder
      json-formatter/
      color-palette/
      regex-tester/
      base64/
    hooks/         # Custom React hooks
    utils/         # Pure utility functions
    App.tsx        # Main app with routing

  ## Git

  - Conventional commits: `feat:`, `fix:`, `chore:`, `docs:`
  - Keep commits small and focused

  ## Important

  - Never use `npm` - always use `yarn`
  - Do not install Tailwind or any CSS framework
  - Do not add comments unless logic is genuinely complex
  - Do not create README.md files unless asked
  