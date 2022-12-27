# Nuxt 3 Minimal Starter with the following additions:

- Setup eslint with nuxt 3 rules.
- Setup eslint airbnb style rules.
- Setup Prettier to format code. (configured to work fine with eslint).
- Setup eslint validation on Vite develop console.
- Setup husky to validate eslint and prettier rules before commits.
- Setup SASS and its loads on Vite.

We recommend that you install the Prettier extension on VS Code and configure it as the default code formatter for JS and Vue files.

Look at the [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

Make sure to install the dependencies:

```bash
# yarn
yarn install
(If you want to use yarn instead of npm, you can replace "npm" with "yarn" in the following files:
  - .husky/pre-commit
  - package.json
)

# npm
npm install

# pnpm
pnpm install --shamefully-hoist
```

## Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

## Production

Build the application for production:

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
