# Eden Hwang — Marketing Portfolio

Brand content, campaign execution, and audience insight.
Porsche Korea · Better Buy · Give Orange Inc. · Rollover

**Live:** https://aoifeeden3.github.io/edenhwang-portfolio/

---

## About

A one-page portfolio covering social content work across four industries: luxury
automotive, a consumer tech startup, a nonprofit, and a food service brand.

It is a single self-contained HTML file. No build step, no dependencies, no
framework. Open `index.html` in any browser and it runs.

```
index.html      the whole site — markup, styles, icons, and scripts
images/         tile photography
README.md
```

## The work

Nineteen pieces across three brands:

- **Porsche Korea** — seven LinkedIn posts written in Korean and English, from model
  launches to quarterly results to the Porsche Do Dream CSR program
- **Better Buy** — four Instagram and TikTok pieces for a browser extension that
  grades products while you shop
- **Give Orange Inc.** — an eight part Instagram campaign for The GIVO-ing Tree, run
  with the NGO Beautifull Learning

Porsche photography is Porsche Korea's, credited on the page. Everything else is mine.

## Design

Built from Animal Crossing, read as a system of rules rather than copied: nothing has
a sharp corner, every object is outlined in warm brown instead of black, the ground is
one flat green printed with tufts, and signs are wooden boards that hang slightly
tilted. Two large calm fields, sky above and grass below, with three small pops —
tulip red, tulip yellow, blossom pink — used sparingly against them.

Four kinds of motion: petals fall across the header, clouds drift, cards hop and
settle when hovered, and the wooden signs sway on their posts. The tree can be shaken,
and one time in four an apple comes down golden. All of it respects
`prefers-reduced-motion`.

## Editing

Everything lives in `index.html`. The `<style>` block opens with design tokens as CSS
custom properties, the `<svg>` block after `<body>` holds the icon set, and each
project is one `<article>`.

To edit on GitHub: open the file, click the pencil icon, change the text, then commit.
The live site updates within a minute or two.

Images are named by project and position — `porsche-01.jpg` to `porsche-07.jpg`,
`betterbuy-01` to `-04`, `giveorange-01` to `-08`. Porsche frames are landscape 4:3 at
1200×900; the Instagram projects are portrait 4:5 at 1000×1250. Filenames are case
sensitive once published, so keep them lowercase. The `images` folder must sit beside
`index.html` — the paths in the file are relative to it.

## Deployment

GitHub Pages, `main` branch, root folder. Settings → Pages.

## Contact

aoifeeden3@gmail.com · [LinkedIn](https://www.linkedin.com/in/edenjhwang)
