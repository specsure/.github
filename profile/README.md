# Specsure

Open tools that keep code within the design system. Everything runs on your machine, in CI or in the browser: no server, no account.

| | |
|---|---|
| **[Token Diff](https://specsure.vercel.app/tools/diff)** | Compare two versions of design tokens in the browser: what was removed or renamed, what changed in each theme, and which version the release needs. |
| **[GitHub Action](https://github.com/marketplace/actions/dsgraph-diff)** | The same report as a comment on every pull request. Fails the check on breaking changes. [See it on a pull request](https://github.com/specsure/action-playground/pull/1). |
| **[CLI](https://www.npmjs.com/package/@dsgraph/cli)** | `npx @dsgraph/cli diff npm:@acme/tokens@1 npm:@acme/tokens@2` |
| **[MCP server](https://specsure.vercel.app/tools/mcp)** | Gives coding agents your tokens, so they write `var(--color-accent)` instead of a hex. |
| **[dsgraph](https://github.com/specsure/specsure)** | The engine behind them: DTCG 2025.10, token JSON and CSS custom properties read as one graph. MIT. |

Next: a Figma plugin that checks variables and styles against your tokens.

[Changelog](https://github.com/specsure/specsure/blob/main/CHANGELOG.md) · [Issues](https://github.com/specsure/specsure/issues)
