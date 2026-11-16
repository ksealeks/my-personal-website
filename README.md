# Ksenia Alekseeva portfolio

Static portfolio for `https://www.kseniaalekseeva.net/`, deployed from GitHub through Vercel.

## Local preview

```sh
python3 -m http.server 4173 --directory dist
```

Then open `http://127.0.0.1:4173/`.

## Vercel

The repository is configured to deploy the `dist` directory. Import the repository into Vercel or run `vercel` from the project root. Do not promote a preview deployment to production until it has been reviewed.

## Project structure

- `dist/index.html` — exact source baseline plus the two requested changes
- `dist/img/my-photo-new.png` — replacement portrait, unchanged from the supplied file
- `dist/img/carousel/` — the seven requested carousel photographs, in source order
- `dist/img/logos/` — original production logo assets
- `dist/robots.txt`, `dist/sitemap.xml`, `dist/llms.txt` — preserved SEO files
- `CONTENT-LINK-COMPARISON.md` — comparison and validation report
