# graft

> [!WARNING]
> This repository is archived. Development continues at [chex-garage](https://github.com/blck-snwmn/chex-garage).

A personal userscript manager as a Chrome extension

## Supported Sites

### gemini.google.com
- Adds an "Open in new tab" button to the conversation list

## Setup

```bash
bun install
bun run build
```

In Chrome, go to `chrome://extensions` → Enable Developer mode → Load the `dist` folder

## Development

```bash
bun run dev
```

## Adding a New Site

1. Create `src/sites/{domain}/index.ts`
2. Add a content_scripts entry to `manifest.json`
