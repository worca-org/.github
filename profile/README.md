<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="worca-logo-dark.svg">
    <img src="worca-logo.svg" alt="Worca" width="320">
  </picture>
</p>

<h3 align="center">Your AI agents, on rails.</h3>

<p align="center">
  Describe the work, get back a reviewed pull request.
</p>

Worca is a free, open-source (MIT) multi-agent pipeline for AI coding agents. You describe the change. A deterministic pipeline clarifies, plans, implements and reviews it. It loops until the work passes its quality gates. It stops only to ask you what matters.

Each run works on its own git branch. Your checkout stays untouched. Finished work arrives as a pull request.

- **Website:** [worca.dev](https://worca.dev)
- **Docs:** [docs.worca.dev](https://docs.worca.dev)
- **Install:** [`@worca/app` on npm](https://www.npmjs.com/package/@worca/app)

## Repositories

- **[worca](https://github.com/worca-org/worca)**: the app. The pipeline, the web UI and the CLI, published as [`@worca/app`](https://www.npmjs.com/package/@worca/app) and the container image `ghcr.io/worca-org/worca`.
- **[worca-platform](https://github.com/worca-org/worca-platform)**: run your own hosted Worca. A multi-tenant management platform on Cloudflare, published as [`@worca/platform`](https://www.npmjs.com/package/@worca/platform) and [`@worca/create-platform`](https://www.npmjs.com/package/@worca/create-platform).

Contributions are welcome in both. Start with each repository's `CONTRIBUTING.md`.
