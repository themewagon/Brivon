# Brivon — Modern Photography Studio HTML Template

A free, production-ready HTML template for commercial photography
studios, editorial photographers, documentary teams, and
visual-arts producers. Editorial-brutalist visual direction
with a **charcoal ground + electric lime accent + ink-black**
palette, a **Boldonse** display family paired with **Inter Tight**
body and **Geist Mono** captions. No editorial serif, no cream
zone — palette is intentionally cool-dark with one saturated accent.
Tokenised, responsive, accessible. No framework, no build step,
no JS dependencies.

## Pages

- `index.html` — Home (typographic hero with floating frame tags, four-stat strip, selected-work grid with seven asymmetric tiles, reverse-tile chapter with pull-quote, seven-card capability bento, two split-image chapters on process and rooms, press strip, three-card journal grid, closing CTA on lime ground)
- `work.html` — Selected work hero, twelve featured projects (mixed editorial / campaign / architecture / food / product / portrait / documentary), case-study chapter on Atrium SS25, twelve-row recent archive list
- `studio.html` — Studio hero, founding chapter, awards strip, six-rule principles bento, two split-image room descriptions (Brooklyn + Berlin), eight-portrait team grid
- `services.html` — Three-tier services hero (Editorial / Campaign / Marque), full rate card, eight-step process grid, six-question FAQ on reverse tile
- `contact.html` — Three-channel hero (new project / press / careers), full intake form with eight fields and country routing, two-room split chapter, three-card press kit

## Tech

- Static HTML, vanilla CSS, vanilla JS (no framework, no build, no dependencies)
- Google Fonts: Boldonse (display), Inter Tight (body, 400 – 700), Geist Mono (captions / tabular)
- Real Pexels photography in `assets/img/` — replace with your own studio work before launch (see `assets/img/CREDITS.md`)
- Reduced-motion friendly, keyboard accessible, semantic landmarks, skip-link, ARIA on interactive controls
- Responsive at 375 / 768 / 1024 / 1440 / 1920

## Design system

All tokens live at the top of `assets/css/styles.css` as CSS custom
properties:

- **Palette** — charcoal ground (`#0A0A0C`), elevated card `#18181C`, paper-ivory text `#F4F4F0`, electric lime accent (`#D4FF3D`), one cobalt micro-accent used once
- **Typography** — uppercase brutalist display, mono captions, line-heights ≥1.22 throughout (Boldonse-safe)
- **Spacing** — 1 → 11 modular scale
- **Motion** — three durations, two easings, full reduced-motion fallback
- **Layout** — three container widths (narrow / default / wide), 12-col asymmetric work grid, 12-col cap bento
- **Shadows** — six elevation levels including a signature lime-tinted shadow on the featured tier card

Adjust the `:root` block to recolor or rescale the whole template.
Change `--lime` to recolor every accent surface across the site.
Replace the font `<link>` in each `.html` to switch type pairings.

## Replacing the placeholders

Every photo in `assets/img/` is sourced from Pexels under their
permissive license (full attribution in `assets/img/CREDITS.md`).
For a real launch:

- Drop in your own portrait, editorial and studio photography for the hero, the selected-work grid, and the team gallery
- Replace `studio-brooklyn.jpg`, `studio-berlin.jpg`, and the process/contact shots with your own studio rooms and on-set work
- Replace the eight `team-*.jpg` portraits with the real people on your team (always with permission)
- Update the project list in `work.html` to reflect your actual archive — twelve featured + a paginated archive list

## Customising the brand mark

The brand mark is a 28×28 electric-lime square with an inverted
"V" cutout — read as a frame mark, a viewfinder, or a chevron
depending on the eye. To swap it, replace `<span class="brand-mark">`
with your own SVG logo, or restyle `.brand-mark` and `.brand-mark::after`
in `styles.css`.

## TM check (informal)

- **Google + Bing search** ("Brivon" + brand + company + photography studio): no active commercial entity using this name in any category
- **Trademark search**: no active marks discovered in the searched class
- **Verdict**: ok to ship · informal clearance, not a legal opinion

## Credit

Built by [html.design](https://html.design/) as a free download —
fork it, ship it, use it. No attribution required.
