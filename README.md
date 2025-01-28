# VitePress Documentation Site

A modern documentation site built with VitePress - a Vite & Vue powered static site generator.

## Features

- 📝 Markdown-centered content authoring
- ⚡️ Lightning fast hot module replacement (HMR)
- 🎨 Customizable theme
- 🔍 Built-in search
- 🚀 Vue-powered features in Markdown

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

```bash
npm install
```

### Development

Start the development server:

```bash
npm run docs:dev
```

The site will be available at `http://localhost:5173`

### Build

Build for production:

```bash
npm run docs:build
```

### Preview Production Build

```bash
npm run docs:preview
```

## Project Structure

```
.
├── docs/
│   ├── .vitepress/
│   │   └── config.ts    # VitePress configuration
│   ├── index.md         # Home page
│   └── example.md       # Example page
└── package.json
```

## Scripts

- `docs:dev` - Start development server
- `docs:build` - Build for production
- `docs:preview` - Preview production build
- `start` - Alias for docs:dev

## License

MIT# vitepress
