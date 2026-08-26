# Heading Jump Fix — Landing Page

Official landing page for **Heading Jump Fix** (Obsidian Community plugin **v1.1.0**).

- Auto-correct scroll position after outline or heading clicks so one click is enough
- Duplicate headings matched by outline order; configurable retry delay / count
- Fully offline — Free & MIT
- Japanese / English toggle, Buy Me a Coffee button

## Live URLs

| Service | URL |
|---------|-----|
| **GitHub** | https://github.com/crossbeat461-a11y/k-tech-heading-jump-fix-lp |
| **Vercel** | https://k-tech-heading-jump-fix-lp.vercel.app/ (after import) |

## Updating for a new plugin version

1. Replace the version string (`v1.1.0`) in `index.html`:
   - `<title>` and meta descriptions
   - hero `#version-badge`
   - footer line
2. Prepend a new `.release` block at the top of the `#changelog` list
   (move the `latest` class to the new entry).
3. Update `sitemap.xml` `<lastmod>` if desired.

## Local preview

```bash
python3 -m http.server 8080
# http://localhost:8080
```

## Deploy

### Vercel (recommended)

1. [Vercel](https://vercel.com/new) → Import Git → `crossbeat461-a11y/k-tech-heading-jump-fix-lp`
2. Framework Preset: **Other** (static)
3. Deploy

CLI (logged in):

```bash
npx vercel --prod
```

## Links

- Community plugins: https://obsidian.md/plugins?id=k-tech-heading-jump-fix
- Plugin repo: https://github.com/crossbeat461-a11y/k-tech-heading-jump-fix
- K-Tech Studio: https://k-tech-lab.vercel.app/
- Buy Me a Coffee: https://buymeacoffee.com/k_tech_studio
