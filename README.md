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

The presentation opens at the local Slidev development URL. Edit `slides.md`, save, and refresh the browser to review changes.

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
