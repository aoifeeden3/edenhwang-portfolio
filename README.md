# Eden Hwang — Marketing Portfolio

Brand content, campaign execution, and audience insight.
Porsche Korea · Better Buy · Give Orange Inc. · Rollover

**Live:** https://aoifeeden3.github.io/edenhwang-portfolio/

---

## About

A one-page portfolio covering social content work across four industries: luxury
automotive, a consumer tech startup, a nonprofit, and a food service brand — plus a
self-directed marketing analytics project.

It is a single self-contained HTML file. No build step, no dependencies, no framework.
Open `index.html` in any browser and it runs.

```
index.html      the whole site — markup, styles, and scripts
images/         tile photography (19 files)
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

Warm cream, sage green, and dusty terracotta — a palette drawn from objects at rest.
Nothing is fully saturated; every colour has been mixed with a little white. Serif
headlines set in italic, a lighter sans underneath for reading.

Motion is quiet but not still: a soft glow follows the cursor through the header,
project numbers lift when hovered, tile titles draw an underline, contact buttons lean
toward the cursor, and a small mark travels the top of the page as you scroll. All of
it respects `prefers-reduced-motion`.

## Editing

Everything lives in `index.html`. The `<style>` block opens with design tokens as CSS
custom properties; each project is one `<article>`.

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
