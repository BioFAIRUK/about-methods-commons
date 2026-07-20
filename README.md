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
| `_sass/_bootstrap_variables.scss` | Brand colours, the Space Grotesk / IBM Plex fonts, radii |
| `_sass/_custom_classes.scss` | Eyebrow label, hero, soft-tint utilities |
| `_config.yml` → `theme_variables` | Logo, theme colour, Google Fonts, top-nav options |
| `assets/img/` | BioFAIR logo (`biofair-logo.svg`) and generated favicons |

Colours and type mirror the design system's `tokens.css` (`--bf-*`): emerald
`#00A070` / emerald-deep `#00785A`, raspberry `#E0115F` / `#B00C4C`, ink
`#14130F`; Space Grotesk (display), IBM Plex Sans (body), IBM Plex Mono (code).

> Emerald-deep `#00785A` is used as the functional `$primary` because vivid
> emerald fails WCAG contrast as text/label colour — this is the design
> system's own rule.

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
