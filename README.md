# Electron + React + TypeScript + Vite

This project is a template for building desktop applications using [Electron](https://www.electronjs.org/), [React](https://react.dev/), [TypeScript](https://www.typescriptlang.org/), and [Vite](https://vitejs.dev/).

## Features

- ⚡ Fast React development with Vite
- 🖥️ Desktop app packaging via Electron
- 🦺 TypeScript for type safety
- 🔬 ESLint for code quality

## Getting Started

### Install dependencies

```sh
npm install
```

### Run React development server

```sh
npm run dev:react
```

### Transpile Electron main process

```sh
npm run transpile:electron
```

### Start Electron app (after building React)

```sh
npm run dev:electron
```

### Build for production

```sh
npm run build
```

## Project Structure

- `src/ui/` — React frontend
- `src/electron/` — Electron main process
- `dist-react/` — Built React app
- `dist-electron/` — Built Electron main process

## Linting

```sh
npm run lint
```

## Preview Production Build

```sh
npm run preview
```

## Configuration

- React/Vite config: [`vite.config.ts`](vite.config.ts)
- Electron entry: [`src/electron/main.ts`](src/electron/main.ts)
- TypeScript configs: [`tsconfig.app.json`](tsconfig.app.json), [`tsconfig.node.json`](tsconfig.node.json)

## License

MIT
