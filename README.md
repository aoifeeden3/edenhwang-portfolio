# edenhwang.com

Marketing portfolio of Eden Hwang — brand content, campaign execution, and audience insight.

**Live site:** https://YOUR-USERNAME.github.io

## What's here

A single-page portfolio covering social content work for Porsche Korea, Better Buy,
and Give Orange. Built as one self-contained HTML file: no build step, no dependencies,
no framework. Open `index.html` in any browser and it runs.

## Design

The visual language is adapted from a Meiji Apollo box — candy red, milk cream, cocoa
brown outlines, blush pink, and one gold reserved for a single reward moment. Flat fills,
heavy strokes, and hard offset shadows throughout, with the carton's die-cut scallop
reused as the hem of the navigation bar. Icons outside the original vocabulary — a bee,
a football, a heart, a camcorder, a sprout — were drawn to the same rules rather than
borrowed.

Four kinds of motion: lucky stars streaking across the header, motifs floating on
independent loops, rows bouncing on hover, and a star burst on click. All of it respects
`prefers-reduced-motion`.

## Editing

Everything lives in `index.html`. The `<style>` block holds design tokens as CSS custom
properties at the top, the `<svg>` block after `<body>` holds the icon set, and each
project is an `<article class="panel">`.

To add a screenshot to a post row, drop the image in an `images/` folder and replace the
`<svg>` inside that row's `post__thumb` with `<img src="images/file.jpg" alt="">`.

## Contact

aoifeeden3@gmail.com · [LinkedIn](https://www.linkedin.com/in/edenjhwang)
