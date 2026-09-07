# Bots Limited (Bots.LT) Documentation

This repository contains the official documentation for **Bots Limited** ([Bots.LT](https://bots.lt)), the cloud platform that lets you build, host, and scale Telegram bots instantly using BLP Language (Bots Limited Python).

## Overview

Bots.LT provides a completely serverless environment to write Telegram bots. No webhooks, no servers, no hassle. The documentation here covers:

- **Getting Started:** Quickstart guides and local CLI usage (`botslt`).
- **BLP Language:** Syntax, variables, and security constraints.
- **Data Storage:** Built-in blazing fast key-value states (`User`, `Bot`, `Api`).
- **Telegram API:** Full wrappers around the Telegram Bot API.

## Running Locally

This documentation is built using [Mintlify](https://mintlify.com/).

To preview the documentation locally, install the Mintlify CLI:

```bash
npm i -g mintlify
```

Run the development server from this repository root:

```bash
mintlify dev
```

Visit `http://localhost:3000` to view the live preview.

## Deployment & Updates

All pages are written in Markdown (`.mdx`). The main navigation configuration is located in `docs.json`.
When pushing changes to the `main` branch, the Mintlify app will automatically deploy the updates to the official documentation site.

## Community & Support

- **Main Platform**: [bots.lt](https://bots.lt)
- **Official Docs Site**: [help.bots.lt](https://help.bots.lt)
- **Telegram Community**: [@bots_lt](https://t.me/bots_lt)
- **Organization**: [JSOrganizations](https://github.com/JSOrganizations)
