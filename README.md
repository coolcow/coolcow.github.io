# coolcow.github.io

Personal Jekyll site for https://coolcow.org.
This README is only a short note for future me.

## Run locally

```bash
bundle install
bundle exec jekyll serve --livereload --host 0.0.0.0 --port 4000
```

Optional build check:

```bash
bundle exec jekyll build
```

## Deployment

- Hosting: GitHub Pages
- Domain über `CNAME`
- Basis-Konfiguration in `_config.yml`

## Projektstruktur (kurz)

- Content: `index.md`
- Layout: `_layouts/home.html`
- Includes: `_includes/footer.html`
- Styles: `assets/main.scss`
- Build-Output: `_site/` (generiert)

## Next things

- Regularly refine the homepage hero/text
- Check footer icons/links
- Run a quick local build after gem updates
