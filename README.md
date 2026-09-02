# Eden Hwang — Marketing Portfolio

Marketing portfolio of Eden Hwang — brand content, campaign execution, and audience insight.

**Live site:** https://aoifeeden3.github.io/edenhwang-portfolio/

## What's here

A single-page portfolio covering social content work for Porsche Korea, Better Buy, and
Give Orange. It is one self-contained HTML file: no build step, no dependencies, no
framework. Open `index.html` in any browser and it runs.

```
index.html    the entire site — markup, styles, icons, and scripts
README.md     this file
```

## Design

The visual language is adapted from a Meiji Apollo box: candy red, milk cream, cocoa brown
outlines, blush pink, and one gold reserved for a single reward moment. Flat fills, heavy
strokes, and hard offset shadows throughout, with the carton's die-cut scallop reused as
the hem of the navigation bar. Icons outside the original vocabulary — a bee, a football, a
heart, a camcorder, a sprout — were drawn to the same rules rather than borrowed.

Four kinds of motion: lucky stars streaking across the header, motifs floating on
independent loops, rows bouncing on hover, and a star burst on click. All of it respects
`prefers-reduced-motion`.

## Editing

Everything lives in `index.html`. The `<style>` block opens with design tokens as CSS custom
properties, the `<svg>` block after `<body>` holds the icon set, and each project is an
`<article class="panel">`.

To edit on GitHub: open `index.html`, click the pencil icon, make the change, then Commit
changes. The live site updates within a minute or two.

To add a screenshot to a post row, create an `images/` folder in the repo and replace the
`<svg>` inside that row's `post__thumb` with `<img src="images/file.jpg" alt="">`.

## Deployment

Served by GitHub Pages from the `main` branch, root folder. Settings → Pages.

## Contact

aoifeeden3@gmail.com · [LinkedIn](https://www.linkedin.com/in/edenjhwang)
