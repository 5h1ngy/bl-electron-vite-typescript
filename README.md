# 🚀 Vanilla-TS

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Electron](https://img.shields.io/badge/Electron-22.x-47848F.svg?logo=electron)
![Vite](https://img.shields.io/badge/vite-4.x-646CFF.svg?logo=vite)
![TypeScript](https://img.shields.io/badge/TypeScript-4.x-3178C6.svg?logo=typescript)

A minimal Electron application built with TypeScript and Vite. Perfect for creating lightweight, cross-platform desktop applications with the added benefits of static typing.

**Topics:** `electron` `typescript` `vite` `cross-platform` `desktop-app` `offline-first` `local-storage` `minimal` `type-safety`

## 📋 Table of Contents
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Recommended IDE Setup](#-recommended-ide-setup)
- [Project Setup](#-project-setup)
- [Package Managers](#-package-managers)
- [Resources](#-resources)

## ✨ Features

- 🔒 Type safety with TypeScript
- 🔄 Hot Module Replacement (HMR) during development
- ⚡ Ultra-fast build with Vite bundler
- 📦 Cross-platform packaging
- 🧩 Native Node.js integration
- 💾 Support for offline data storage
- 🔍 TypeScript linting with ESLint
- 🎨 Code formatting with Prettier
- 📝 TypeScript type declarations
- 📤 Import/export capability for data

## 🗂️ Project Structure

```
bl-electron-vite-typescript/
├── build/              # Build resources and configuration
├── dist/               # Build output directory
├── out/                # Packaged application output
├── src/
│   ├── main/           # Main process code
│   │   └── index.ts    # Main entry point
│   ├── preload/        # Preload scripts
│   │   └── index.ts    # Preload entry point
│   └── renderer/       # Renderer process code
│       ├── index.html  # HTML template
│       └── index.ts    # Renderer entry point
├── .eslintrc           # ESLint configuration
├── electron-builder.yml # Electron builder configuration
├── package.json        # Project dependencies and scripts
├── tsconfig.json       # TypeScript configuration
└── vite.config.ts      # Vite configuration
```

## 🛠️ Recommended IDE Setup

- [VSCode](https://code.visualstudio.com/) + [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) + [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

## 🚀 Project Setup

### 📥 Install

```bash
$ pnpm install
```

### 🔧 Development

```bash
$ pnpm dev
```

### 📦 Build

```bash
# For windows
$ pnpm build:win

# For macOS
$ pnpm build:mac

# For Linux
$ pnpm build:linux
```

## 📦 Package Managers

This project supports multiple package managers. Here's how to use each one:

### NPM

NPM is the default package manager for Node.js.

**Install NPM:**
```bash
# Included with Node.js installation
```

**Setup project with NPM:**
```bash
# Install dependencies
$ npm install

# Run development server
$ npm run dev

# Build application
$ npm run build:win
$ npm run build:mac
$ npm run build:linux
```

**Key features:**
- 📚 Vast package ecosystem
- 🔒 Hierarchical node_modules structure
- 📋 Package.json for dependency management

### Yarn

Yarn is a fast, reliable, and secure alternative to NPM.

**Install Yarn:**
```bash
# Install using NPM
$ npm install -g yarn
```

**Setup project with Yarn:**
```bash
# Install dependencies
$ yarn

# Run development server
$ yarn dev

# Build application
$ yarn build:win
$ yarn build:mac
$ yarn build:linux
```

**Key features:**
- ⚡ Faster installation speeds
- 📦 Offline caching
- 🔒 Better security with checksums
- 📋 yarn.lock for deterministic installations

### PNPM

PNPM is a disk-space efficient package manager.

**Install PNPM:**
```bash
# Install using NPM
$ npm install -g pnpm
```

**Setup project with PNPM:**
```bash
# Install dependencies
$ pnpm install

# Run development server
$ pnpm dev

# Build application
$ pnpm build:win
$ pnpm build:mac
$ pnpm build:linux
```

**Key features:**
- 💾 Disk space savings through symlinks
- 🚀 Fast installation speeds
- 🔄 Content-addressable storage
- 📋 pnpm-lock.yaml for dependency lock

### Comparison

| Feature               | NPM     | Yarn    | PNPM    |
|-----------------------|---------|---------|---------|
| Disk usage            | High    | High    | Low     |
| Installation speed    | Slow    | Fast    | Fastest |
| Parallel installations| Limited | Yes     | Yes     |
| Workspace support     | Limited | Good    | Best    |
| Offline mode          | Limited | Good    | Good    |
| Security              | Good    | Better  | Better  |

## 📚 Resources

- [Electron Documentation](https://www.electronjs.org/docs)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [Vite Documentation](https://vitejs.dev/guide/)
- [NPM Documentation](https://docs.npmjs.com/)
- [Yarn Documentation](https://yarnpkg.com/getting-started)
- [PNPM Documentation](https://pnpm.io/motivation)
