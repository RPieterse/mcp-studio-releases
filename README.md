# MCP Studio Releases

Signed release bundles for [MCP Studio](https://rpieterse.github.io/mcp-studio-releases/), plus the static assets the app fetches at runtime.

**Download & docs:** <https://rpieterse.github.io/mcp-studio-releases/>

This repo exists so the Tauri auto-updater (which fetches via plain HTTP, no GitHub auth) can pull updates. The source code lives in the private `mcp-studio` repo. What's published here:

- Signed desktop binaries + `latest.json` (in the [releases](https://github.com/RPieterse/mcp-studio-releases/releases) tab).
- `index.html` + `docs.html` — public download / docs site served via GitHub Pages.
- `gallery.json` — curated registry of installable third-party MCPs. Studio fetches it on demand for `/gallery` and the Settings → Gallery tab. Pull requests welcome.
