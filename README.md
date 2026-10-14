# Mintlify Demo Boilerplate

A small starter project for learning Mintlify with a fictional product named TaskFlow. It is independent of any company or production documentation repository.

## Requirements

- Node.js 20.17.0 or newer (use a current LTS release)
- npm
- Git (optional for local preview, required for repository workflows)

## Run locally

1. Open a terminal in this folder.
2. Install or update the Mintlify CLI:

   ```bash
   npm install -g mint@latest
   ```

3. Start the local documentation server:

   ```bash
   mint dev
   ```

4. Open http://localhost:3000.

## Files

- `docs.json`: site settings and navigation
- `index.mdx`: homepage
- `quickstart.mdx`: quickstart page
- `guides/first-guide.mdx`: sample guide
- `logo/`: simple SVG logos
- `public/favicon.svg`: favicon

## Customize

Edit the MDX files, save, and check the local preview. When adding a page, create its `.mdx` file and add its path (without the extension) to the `navigation.pages` list in `docs.json`.

This is a learning scaffold. It does not include a deployed site, API credentials, or a connection to any production service.

Official references:
- https://mintlify.com/docs/quickstart
- https://mintlify.com/docs/cli
- https://mintlify.com/docs/navigation
- https://mintlify.com/docs/components
