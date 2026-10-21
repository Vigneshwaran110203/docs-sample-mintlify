# TaskFlow Developer Hub — Mintlify Starter demo

A fictional documentation site for demonstrating the current free Mintlify Starter plan.

## Included

- `docs.json` navigation with documentation and API reference tabs
- MDX pages with frontmatter, Cards, Notes, Warnings, tables, and code examples
- OpenAPI 3.0 specification with GET, POST, PATCH, DELETE operations
- Interactive API playground configuration
- cURL, Python, and JavaScript example languages
- SEO-friendly page titles and descriptions
- Custom SVG logos and favicon
- Manager demo checklist

## Current Starter plan notes

Mintlify's current pricing page lists Starter at $0/month with up to five editor seats. Included features list custom domain, web editor, authentication, Git sync, search, API playground, MCP server, built-in/custom components, custom CSS/JS, SEO/GEO and agent optimizations.

The Assistant, writing agent, automations, preview deployments, analytics, password authentication, and unlimited editor seats are listed as Pro/Enterprise features. Plan details can change; verify the official page before presenting:
https://www.mintlify.com/pricing

## API demo disclaimer

The API playground points to `https://jsonplaceholder.typicode.com`, a public mock API. GET endpoints return sample data. POST/PATCH/DELETE are simulated and do not persist changes. Never enter real credentials or confidential information.

## Run locally

```bash
npm install -g mint
mint dev
```

Run commands from this folder, where `docs.json` is located. Open http://localhost:3000.

Validate the OpenAPI file:

```bash
mint openapi-check openapi.json
```

## Publish on Starter

1. Create/sign in to a Mintlify account.
2. Push this folder to a GitHub repository.
3. Connect the repository in the Mintlify dashboard.
4. Publish to the provided Mintlify subdomain.
5. Test hosted search, API playground, and navigation.
6. Configure a custom domain if you have one.

Some features such as hosted search, domain configuration, web editor, authentication, and MCP are best demonstrated on the hosted site; `mint dev` is primarily the local content preview.

## 5–8 minute manager demo

1. Show the homepage and navigation.
2. Open Quickstart and point out MDX components and code samples.
3. Search for “authentication” on the hosted site.
4. Open API Reference → Get a task, set ID to `1`, and send the request.
5. Show the POST request body and explain that writes are simulated.
6. Show `docs.json`, an MDX page, and `openapi.json` in the repository.
7. Explain which features are Starter versus paid.
