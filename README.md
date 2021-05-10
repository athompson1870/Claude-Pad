# Claude-Pad

A monorepo for tools including browser extensions and model instructions.

## Contents

| Directory | Description |
|-----------|-------------|
| [extensions/chrome](./extensions/chrome) | **Thinking Claude** — Chrome extension that enhances Claude's thinking process (React, TypeScript, Webpack) |
| [extensions/chrome_v0](./extensions/chrome_v0) | Legacy Chrome extension (deprecated) |
| [extensions/firefox](./extensions/firefox) | Firefox extension |
| [model_instructions](./model_instructions) | Model instruction versions and changelogs |

## Quick start

- **Chrome extension**: See [extensions/chrome/README.md](./extensions/chrome/README.md) for install, build, and development.
- **Root**: Uses [Husky](https://typicode.github.io/husky/) for git hooks; run `npm install` (or `bun install`) once to set up.
