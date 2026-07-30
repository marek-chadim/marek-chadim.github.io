# marek-chadim.github.io

Personal academic website. Design adapted from [chrisconlon/chrisconlon.github.io](https://github.com/chrisconlon/chrisconlon.github.io) (Daleri Single template by Andreas Viklund), recolored in Yale blue.

## Deploy (one time, ~5 minutes)

1. Create a new **public** repo on GitHub named exactly `marek-chadim.github.io`.
2. Push:

```bash
cd website
git init && git add -A && git commit -m "feat: initial site"
git remote add origin git@github.com:marek-chadim/marek-chadim.github.io.git
git push -u origin main
```

4. The site goes live at https://marek-chadim.github.io within a minute or two (Settings → Pages should show "Deploy from branch: main" automatically for a repo with this name).

## Maintain

- **CV**: overwrite `cv.pdf` and push.
- **New paper**: add an `<li>` in `research.html` under Working Papers.
- **Colors/fonts**: everything lives in `yale-blue.css` (CSS variables at the top).

## Files

- `index.html` — home: fields, blurb, news, contact + links
- `research.html` — working papers (locally hosted PDFs), work in progress, code portfolio
- `media.html` — press coverage (CES award, Lindau, Yale predoc conference, Econometric Game) + policy output of RA projects
- `chadim_markups_procurement.pdf` / `chadim_markups_slides.pdf` — hosted paper + slides; add future paper PDFs alongside
- `cv.pdf` — current CV (July 2026)
- `yale-blue.css` — stylesheet
- `favicon.png` / `favicon.ico` — "MC" tab icon
- `404.html` — custom not-found page
- `photo.jpg` — headshot (400×400)

## Remember

- Update the "Last updated" footer date (bottom of index.html and research.html) when you push changes.
- Once the paper is on SSRN, create a Google Scholar profile and add the link next to the Tobin/GitHub/LinkedIn row on the home page.
