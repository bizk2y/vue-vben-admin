# Project Overview

This is a monorepo for `vue-vben-admin`, a free and open source middle and back-end template. It is built with Vue 3, Vite, and TypeScript, and uses `pnpm` for package management and `turbo` for monorepo orchestration.

The project is structured as a monorepo with the following components:

- **Apps**: Contains the main applications, including `web-antd`, `web-ele`, and `web-naive`, which are different UI framework implementations of the admin template.
- **Packages**: Contains shared packages used by the applications, such as `constants`, `effects`, `icons`, `locales`, `preferences`, `stores`, `styles`, `types`, and `utils`.
- **Docs**: Contains the documentation for the project, built with VitePress.
- **Internal**: Contains internal packages used for development, such as linting configs, tsconfig, and vite-config.
- **Playground**: A development environment for testing components and features.
- **coreq**: CoreQ development environment.

# Building and Running

## Installation

To install the dependencies, run the following commands:

```bash
npm i -g corepack
pnpm install
```

## Development

To start the development server for a specific application, run one of the following commands:

- `pnpm dev:antd`: Starts the Ant Design version of the application.
- `pnpm dev:ele`: Starts the Element Plus version of the application.
- `pnpm dev:naive`: Starts the Naive UI version of the application.
- `pnpm dev:docs`: Starts the documentation site.
- `pnpm dev:play`: Starts the playground.

To run all applications in development mode, use:

```bash
pnpm dev
```

## Building

To build a specific application, run one of the following commands:

- `pnpm build:antd`: Builds the Ant Design version of the application.
- `pnpm build:ele`: Builds the Element Plus version of the application.
- `pnpm build:naive`: Builds the Naive UI version of the application.
- `pnpm build:docs`: Builds the documentation site.
- `pnpm build:play`: Builds the playground.

To build all applications, use:

```bash
pnpm build
```

## Testing

- `pnpm test:unit`: Runs unit tests using Vitest.
- `pnpm test:e2e`: Runs end-to-end tests using Playwright.

# Development Conventions

- **Commit Messages**: The project follows the [Conventional Commits](https://www.conventionalcommits.org/) specification.
- **Linting**: The project uses ESLint for code style and Prettier for code formatting.
- **Type Checking**: The project uses TypeScript for static type checking.
- **Contribution**: Contributions are welcome! Please follow the guidelines in `.github/contributing.md`.

# 변경

- coreq 하위 폴더만 파일 변경하고 다른 파일을 확인 받을 것.
-
