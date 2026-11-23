# Contributing to Awesome Antigravity Plugins

Thank you for helping curate the **Google Antigravity** plugin ecosystem! Contributions in both English and Chinese are warmly welcome.

## Submission Criteria

Before opening a Pull Request or Issue, please verify that the project meets the following standards:

1. **Purpose-Built for Google Antigravity**: The project must ship a valid Antigravity `plugin.json` bundle, Auxiliary Pane `UI Sidecar`, CLI `statusLine`, `SKILL.md` suite, Lifecycle Hook, or ACP/MCP integration explicitly designed for Antigravity (`agy` CLI or Antigravity 2.0 Desktop/IDE).
2. **Clear Documentation & Install Path**: The repository must include a clear `README.md` with installation steps, required runtimes/platforms, and an open-source license (or be an official/verified Antigravity Marketplace plugin).
3. **Privacy & Terms Compliance**:
   - Must use documented extension points (`~/.gemini/config/plugins/`, `Sidecars`, `Skills`, `Rules`, `Hooks`, `MCP`, `ACP`, `statusLine`).
   - **Zero tolerance** for credential/token harvesting, quota-bypass proxies, binary cracks, or tools that violate Google Antigravity Terms of Service.

## How to Add a Plugin via Pull Request

1. Fork this repository and create a new branch (`git checkout -b add-<plugin-name>`).
2. Add your entry to **both** [`README.md`](./README.md) (English) and [`README_CN.md`](./README_CN.md) (Simplified Chinese) under the most fitting category.
3. Follow the concise single-bullet format:
   ```markdown
   - **[Plugin Name](https://github.com/owner/repo)** — Concise 1–2 sentence description highlighting what it does and which extension surfaces (`Sidecar`, `Skill`, `MCP`, `Hooks`, `Rules`) it uses.
   ```
4. Keep descriptions objective, crisp, and free of marketing superlatives ("the best", "revolutionary", etc.).
5. Open a Pull Request describing your plugin and showing a quick screenshot or demo GIF if it includes a UI Sidecar or HUD!
