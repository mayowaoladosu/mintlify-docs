# LayerRail Docs

This repository contains the Mintlify documentation site for LayerRail.

## Local preview

Install the Mintlify CLI:

```bash
npm i -g mint
```

Run the docs locally:

```bash
mint dev
```

The preview runs at `http://localhost:3000`.

## Structure

- `docs.json` configures navigation, branding, navbar links, and footer links.
- `overview.mdx` is the main docs overview.
- Product docs live in folders such as `virtual-machines`, `managed-postgresql`, `managed-kubernetes`, `networking`, `github-actions-integration`, and `ai-inference`.
- API docs live in `api-reference`.
- Operational docs live in `architecture`, `security`, and `about`.

## Writing style

- Use clear, direct developer-facing language.
- Prefer short task-focused pages.
- Use `Steps`, callouts, tables, and code blocks where they make the page easier to follow.
- Keep wording LayerRail-native. Do not copy third-party docs text.

