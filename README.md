# BioFAIR Method Commons

A Jekyll site for the **BioFAIR Method Commons** — the shared, FAIR catalogue
of methods, protocols and analytical workflows for the BioFAIR programme.

Built on the [ELIXIR Toolkit Theme](https://github.com/ELIXIR-Belgium/elixir-toolkit-theme)
and styled with the [BioFAIR Design System](https://github.com/BioFAIRUK/biofair-design-system).

## Branding

The BioFAIR look is applied through the theme's supported extension points —
no theme files are forked:

| File | Purpose |
|---|---|
| `_sass/_bootstrap_variables.scss` | Brand colours, fonts, radii |
| `_sass/_custom_classes.scss` | Eyebrow label, hero, strapline, tint utilities |
| `_config.yml` → `theme_variables` | Logo, theme colour, Google Fonts, top-nav options |
| `assets/img/` | BioFAIR logo (`biofair-logo.png`) and generated favicons |

Colours and type follow the official **BioFAIR Brand Guidelines (2024)**
(kept locally under `notes/`, which is git-ignored and not published):

- **Green** `#54A174`, **pink** `#AC2650`, **black** `#000000`, secondary
  background grey `#ECEFEE`.
- Type: the brand's **Avenir Next** is not licensable for web embedding, so
  **Nunito Sans** (its closest free substitute) is used for display + body,
  and **PT Sans Caption** (free) matches the logo strapline.

> Two web-only adjustments: the functional `$primary` uses a slightly
> darkened green `#3E7D57` (≈4.9:1 on white) because the brand green fails
> WCAG AA as small text; the vivid `#54A174` is kept for large/decorative
> use (e.g. the hero eyebrow on black).

## Run locally

```bash
bundle install
bundle exec jekyll serve
# → http://localhost:4000
```

## Deploy

- **GitHub Pages via Actions** (recommended): push to `main`; the workflow in
  `.github/workflows/jekyll.yml` builds and deploys. Enable
  *Settings → Pages → Source: GitHub Actions*.
- **Plain GitHub Pages**: in `_config.yml`, swap the `theme:` line for the
  commented-out `remote_theme:` line.

## Content

This is an overview site for the Method Commons project.

- `index.md` — home (hero + what it's for + the three BioFAIR Commons)
- `pages/about.md`
- Navigation: `_data/topnav.yml`, `_data/sidebars/main.yml`, `_data/footer.yml`
