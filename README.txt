Preview images for the tiles in index.html.

Already here (Porsche Korea press photography, 1200x900, 4:3):
  porsche-01  911 GTS Media Track Experience
  porsche-02  911 Spirit 70 and 911 GT3
  porsche-03  2025 Dream Up Concert
  porsche-04  Bee'lieve in Dreams-Park gardening day
  porsche-05  Turbo for Dreams - Football
  porsche-06  Porsche AG Q3 results
  porsche-07  Dream Circle, two new schools

Still to add, same naming, landscape 4:3, about 1200x900, under 400KB:
  betterbuy-01 ... betterbuy-04
  giveorange-01 ... giveorange-08

Any tile without an image falls back to a typographic card, so the page
never looks broken while these are missing.

For a video preview, replace the <img> in that tile with:
  <video src="videos/name.mp4" muted loop playsinline preload="metadata"
         poster="images/name.jpg"></video>
It plays on hover. Keep clips under 6 seconds and 5MB.
