# DeepSeek Harness

Personal fork of [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness), maintained for my own development and experimentation.

DeepSeek Harness (`dsh`) is an open-source agent harness originally developed by [DeepSeek AI](https://deepseek.com). It uses a plugin-based architecture and is powered by [Cordis](https://github.com/cordiverse/cordis).

> This fork is used directly from source and may diverge from upstream over time.

## Run from source

Requirements:

- Node.js
- pnpm

Clone and build:

```sh
git clone https://github.com/Yarpii/deepseek-harness.git
cd deepseek-harness
pnpm install
pnpm run build
pnpm dsh web
```

The Web UI is served at `http://127.0.0.1:3080` by default.

## Development

Project documentation is available in:

- [Development guide](docs/development.md)
- [Architecture documentation](docs/architecture.md)
- [Agent instructions](AGENTS.md)

## Upstream

Original project: [deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness)

## License

[MIT](LICENSE)

Third-party dependencies and their licenses are listed in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
