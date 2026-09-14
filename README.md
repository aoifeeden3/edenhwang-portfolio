# Eden Hwang — Marketing Portfolio

Brand content, campaign execution, and audience insight.
Porsche Korea · Better Buy · Give Orange Inc. · Rollover

**Live:** https://aoifeeden3.github.io/edenhwang-portfolio/

---

## What's in here

Three versions of the same portfolio. Same work, same writing, three different
design languages — each one built by reading a piece of visual source material as a
system of rules, then rebuilding those rules as a website rather than copying the
picture.

| Folder | Version | Built from |
|---|---|---|
| `/` | Candy | A Meiji Apollo box: candy red, cocoa outlines, hard offset shadows, a lucky star you can shake loose |
| `/editorial/` | Strawberry matcha | `#F9D1D9` against `#838F58` — pink as the ground, green as the ink |
| `/crossing/` | Island | Animal Crossing: rounded everything, a lawn, wooden signs, and a tree that drops apples |

Each is one self-contained HTML file. No build step, no dependencies, no framework.
Open `index.html` in a browser and it runs.

```
index.html              candy version
editorial/index.html    strawberry matcha version
editorial/images/       tile photography
crossing/index.html     island version
crossing/images/        tile photography
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

## Editing

Everything lives inside each `index.html`. The `<style>` block opens with design
tokens as CSS custom properties, the `<svg>` block after `<body>` holds the icon set,
and each project is one `<article>`.

To edit on GitHub: open the file, click the pencil icon, change the text, commit.
The live site updates within a minute or two.

Images are named by project and position — `porsche-01.jpg` through `porsche-07.jpg`,
`betterbuy-01` to `-04`, `giveorange-01` to `-08`. Porsche frames are landscape 4:3
at 1200×900; the Instagram projects are portrait 4:5 at 1000×1250. Filenames are
case sensitive once published, so keep them lowercase.

## Deployment

GitHub Pages, `main` branch, root folder. Settings → Pages.

## Contact

aoifeeden3@gmail.com · [LinkedIn](https://www.linkedin.com/in/edenjhwang)
