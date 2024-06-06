<img src="media/cover.png" width="100%" align="center" />

<br />

<div align="center">

[![Build](https://img.shields.io/github/actions/workflow/status/terai-labs/terai/release.yml?branch=master)](https://github.com/terai-labs/terai/actions/workflows/release.yml)
[![Tests Coverage](https://img.shields.io/coverallsCoverage/github/terai-labs/terai)](https://coveralls.io/github/terai/terai)
[![Language](https://img.shields.io/badge/language-TypeScript-blue.svg)](https://www.typescriptlang.org)
[![License](https://img.shields.io/github/license/terai/terai)](https://www.npmjs.com/package/@terai-labs/terai)

</div>

<div align="center">
  <b>Terai is a modern localization framework for Javascript. Built with the open source community and optimized for developer experience in the frameworks you love.</b>
</div>

<div align="center">
  <h4>
    <a href="https://terai-labs.github.io/terai">
      Website
    </a>
    <span> | </span>
    <a href="https://terai-labs.github.io/terai/docs">
      Documentation
    </a>
    <span> | </span>
    <a href="https://github.com/terai-labs/terai/issues">
      Issues
    </a>
    <span> | </span>
    <a href="https://github.com/terai-labs/terai/contributing">
      Contributing
    </a>
    <span> | </span>
    <a href="https://github.dev/terai/terai/blob/master/CHANGELOG.md">
      Changelog
    </a>
  </h4>
</div>

> [!WARNING]  
> **Terai** is currently in development preview with unstable dependencies.
While not planned, we may need to introduce breaking changes in these dependencies on the road to v1.0.

## Introduction

**Terai** is a developer-first open-source localization framework for JavaScript that aims to remove the pain in the localization process.

Workflow can be broken down into 3 steps:

- 1️⃣ **Develop**: incorporate your translation source messages into your project using our dedicated SDKs.
- 2️⃣ **Extract**: streamline your extraction process by automatically gathering all the messages within your project.
- 3️⃣ **Translate**: use your defined translator to get your localized messages.

More documentation available at [https://terai-labs.github.io/terai](https://terai-labs.github.io/terai).

## Features

- 🚀 **Speed**: Remove the pain in the localization process. Translate your products **10x faster**.
- 🧑‍💻 **Developer-focused**: One of our main goal was improving the developer experience. No more looking for keys in your source code, no more editing localisation files, and no more manual exporting data for translators.
- 🏆 **Javascript-based**: designed to be used in any javascript-based environment with specific integrations for all major frameworks: Node, React, Next, Vite...
- 🤖 **AI Translation**: Let the machines work for you. We natively support ChatGPT, Google Translate, and AWS translate (and more to come).
- ⌨️ **CLI**: Use your terminal with the CLI.
- 🕋 **Cache**: Don’t translate the same string twice. Translation cache reuses strings you’ve already translated.
- 🌱 **Lightweight**: offer your product to your audience in the way they understand better with just a few KB.
- ✂️ **Code splitting**: Split your translation files with ease. Just import the messages your user needs to see.
- 🐙 **GIT**: Use your well-known version-control systems for storing translations.
- 💎 **TypeScript**: Full-written in TypeScript.
- ⭐️ **MIT Licensed**: Free for personal and commercial use.

## Packages

| Package | Description | Version | Size | Downloads |
| :------ | :---- |  :-----: | :--: | :-------: |
| `@terai/dev` | The user-facing package for **Terai** | [![Version](https://img.shields.io/npm/v/@terai/dev.svg?logo=npm)](https://www.npmjs.com/package/@terai/dev) | [![Size](https://img.shields.io/bundlephobia/minzip/@terai/dev)](https://bundlephobia.com/result?p=@terai/dev) | [![NPM](https://img.shields.io/npm/dm/@terai/dev.svg?&logo=npm)](https://www.npmjs.com/package/@terai/dev) |
| `@terai/react` | **Terai** for React.js | [![Version](https://img.shields.io/npm/v/@terai/react.svg?logo=npm)](https://www.npmjs.com/package/@terai/react) | [![Size](https://img.shields.io/bundlephobia/minzip/@terai/react)](https://bundlephobia.com/result?p=@terai/react) | [![NPM](https://img.shields.io/npm/dm/@terai/react.svg?&logo=npm)](https://www.npmjs.com/package/@terai/react) |
| `@terai/vite` | **Terai** for Vite | [![Version](https://img.shields.io/npm/v/@terai/vite.svg?logo=npm)](https://www.npmjs.com/package/@terai/vite) | [![Size](https://img.shields.io/bundlephobia/minzip/@terai/vite)](https://bundlephobia.com/result?p=@terai/vite) | [![NPM](https://img.shields.io/npm/dm/@terai/vite.svg?&logo=npm)](https://www.npmjs.com/package/@terai/vite) |
| `@terai/next` | **Terai** for Next.js | [![Version](https://img.shields.io/npm/v/@terai/next.svg?logo=npm)](https://www.npmjs.com/package/@terai/next) | [![Size](https://img.shields.io/bundlephobia/minzip/@terai/next)](https://bundlephobia.com/result?p=@terai/next) | [![NPM](https://img.shields.io/npm/dm/@terai/next.svg?&logo=npm)](https://www.npmjs.com/package/@terai/next) |
| `@terai/node` | **Terai** for Node.js | [![Version](https://img.shields.io/npm/v/@terai/node.svg?logo=npm)](https://www.npmjs.com/package/@terai/node) | [![Size](https://img.shields.io/bundlephobia/minzip/@terai/node)](https://bundlephobia.com/result?p=@terai/node) | [![NPM](https://img.shields.io/npm/dm/@terai/node.svg?&logo=npm)](https://www.npmjs.com/package/@terai/node) |

## Getting Started

Visit <a aria-label="terai learn" href="https://terai-labs.github.io/terai/learn">https://terai-labs.github.io/terai/learn</a> to get started with **Terai**.

## Documentation

Visit [https://terai-labs.github.io/terai/docs](https://terai-labs.github.io/terai/docs) to view the full documentation.

## Community

The **Terai** community can be found on [GitHub Discussions](https://github.com/terai/terai/discussions), where you can ask questions, voice ideas, and share your projects.

Our [Code of Conduct](https://github.com/terai/terai/blob/master/CODE_OF_CONDUCT.md) applies to all **Terai** community channels.

## Contributing

Please see our [contributing.md](/contributing.md).

### Good First Issues

We have a list of [good first issues](https://github.com/terai/terai/labels/good%20first%20issue) that contain bugs that have a relatively limited scope. This is a great place to get started, gain experience, and get familiar with our contribution process.

## Authors

- Hugo Corta ([@hugocxl](https://github.com/hugocxl))

## License

MIT License © 2023-Present [Hugo Corta](https://github.com/hugocxl)
