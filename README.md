# UTM Web & Digital Services Presentations

Markdown-based Slidev presentations for UTM Web & Digital Services proposals, briefings, and organizational planning.

## Project structure

- `slides.md` — main presentation source
- `public/images/` — image assets
- `.github/workflows/deploy-pages.yml` — manual GitHub Pages build workflow
- `package.json` — local development and build commands

## Local development

```bash
npm install
npm run dev
```

The presentation opens at the local Slidev development URL, normally `http://localhost:3030`. Slidev reloads the presentation as you edit `slides.md`.

## Preview options

### Local computer

```bash
git clone https://github.com/sharulhafiz/utm-web-presentations.git
cd utm-web-presentations
npm install
npm run dev
```

Open the URL shown in the terminal. This is the recommended workflow because edits are visible immediately.

### GitHub Codespaces

Open the repository on GitHub, choose **Code → Codespaces → Create codespace on main**, then run:

```bash
npm install
npm run dev -- --host 0.0.0.0
```

Open forwarded port `3030` from the Codespaces **Ports** panel.

### GitHub Pages

The repository includes a manual workflow. Open **Actions → Build Slidev presentation → Run workflow**. After it succeeds, GitHub shows the Pages URL in the deployment environment.

The repository is private and Pages has not been enabled automatically during development.

## Build

```bash
npm run build
```

For GitHub Pages:

```bash
npm run build -- --base /utm-web-presentations/ --without-notes
```

The Pages workflow is intentionally manual during content development. Enable automatic deployment only after the deck is approved.

## Editing conventions

- Separate slides with `---`.
- Keep slide text concise; move explanations into speaker notes.
- Prefer editable Markdown, tables, Mermaid diagrams, and CSS over flattened screenshots.
- Use `layout: two-cols` for text and image comparisons.
- Use `layout: image` for full-bleed visual slides.

## Reference

Slidev documentation: https://sli.dev/
