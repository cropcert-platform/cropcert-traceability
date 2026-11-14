# 🖥️ cropcert-traceability

> Traceability application for CropCert

![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg) ![Language](https://img.shields.io/badge/language-TypeScript-3178C6?logo=typescript&logoColor=white) ![Part of](https://img.shields.io/badge/part%20of-CropCert%20Platform-2e7d32.svg)

## 🌱 Overview

The traceability application of the CropCert platform, originally developed as `traceability-mern` (a MERN-stack project). It supports tracking coffee along the supply chain to enable certification and better market access for small growers.

This repository is part of the [CropCert Platform](https://github.com/cropcert-platform), an open-source platform for crop certification and traceability that helps small growers add value to their crop and reach better markets.

## ✨ Features

- Supply-chain traceability for coffee
- Built on the MERN stack lineage
- Written in TypeScript

## 🚀 Getting started

### 📋 Prerequisites

- [Node.js](https://nodejs.org/) (LTS recommended)
- [npm](https://www.npmjs.com/)
- [MongoDB](https://www.mongodb.com/)
- Running instances of the backend services this module talks to

### 🔧 Build & run

1. Clone the repository
2. Install dependencies
   ```bash
   npm install
   ```
3. Edit the '.env.example' file and rename it to '.env'
4. Run the server
   ```bash
   npm run dev
   ```
5. The server will be running on port 5500

```bash
git clone https://github.com/cropcert-platform/cropcert-traceability.git
cd cropcert-traceability
npm install      # or: yarn install
npm run dev      # or: yarn dev
```

Check the `scripts` section of `package.json` for the exact commands available, including build and production start.

## 📁 Project structure

```text
.
├── package.json     # Dependencies and scripts
├── src/             # Application source code
└── LICENSE
```

## 🔗 Related repositories

| Repository | Description |
|---|---|
| [cropcert-ui](https://github.com/cropcert-platform/cropcert-ui) | Web front-end that brings all CropCert modules together |
| [cropcert-odk](https://github.com/cropcert-platform/cropcert-odk) | ODK (Open Data Kit) integration for CropCert |

See all repositories in the [cropcert-platform](https://github.com/cropcert-platform) organisation.

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/my-change`
3. Commit your changes with clear messages
4. Push the branch and open a pull request

For bugs and feature requests, please [open an issue](https://github.com/cropcert-platform/cropcert-traceability/issues).

## 📄 License

Distributed under the **Apache License 2.0**. See [`LICENSE`](LICENSE) for details.

## 🙏 Acknowledgements

This repository is a fork of [biodiv-platform/traceability-mern](https://github.com/biodiv-platform/traceability-mern) maintained for the CropCert platform. Thanks to the original authors and the [biodiv-platform](https://github.com/biodiv-platform) community.
