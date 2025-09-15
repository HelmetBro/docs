# Blooio Messaging API Docs

This repository contains the documentation for the Blooio Messaging API (v3). The site is built with Mintlify and documents all endpoints, webhooks, and usage guides.

## Local development

Install the Mintlify CLI to preview changes locally:

```
npm i -g mint
```

Start the dev server from the repository root (where `docs.json` lives):

```
mint dev
```

Open `http://localhost:3000` to view the docs.

## Structure

- `api-reference/` — Endpoints, webhooks, and errors
- `index.mdx` — Homepage
- `quickstart.mdx` — Send your first message and set up webhooks
- `docs.json` — Navigation, theme, and site configuration

## Contributing

Open a PR for updates or fixes. Ensure examples are accurate and tested. Do not include secrets in code samples.

