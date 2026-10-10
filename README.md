# UI-UX-PRO

Project-scoped install of [UI UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) (v2.13.0, upstream commit `50d8a7d`) for Claude Code.

Skills in `.claude/skills/`: `ui-ux-pro-max`, `design-system`, `design`, `brand`, `banner-design`, `slides`, `ui-styling`. Claude Code loads them automatically when you open this repo.

Quick test:

```bash
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "beauty spa landing page" --design-system
```

Upstream license (MIT): `.claude/skills/LICENSE-ui-ux-pro-max`.

## 21st.dev MCP

`.mcp.json` registers the [21st.dev](https://21st.dev) MCP server (generated with `npx @21st-dev/cli@latest init --client claude --write`).
Get an API key at https://21st.dev/settings/api-keys and set it as `API_KEY_21ST` in your environment — never commit the key itself.
