`zhmiscellany_ocr`,
===


A collection of OCR (image text recognition) functions made by me (zh).
---

[Introduction](https://github.com/zen-ham/zhmiscellany_ocr/tree/master#Introduction) \
[Usage examples](https://github.com/zen-ham/zhmiscellany_ocr/tree/master#Usage-examples) \
[Documentation](https://github.com/zen-ham/zhmiscellany_ocr/tree/master#Documentation)

---

Introduction
===

Can be installed with `pip install zhmiscellany_ocr`

The git repository for this package can be found [here](https://github.com/zen-ham/zhmiscellany_ocr). The docs also look nicer on github.

If you want to reach out, you may add my on discord at @z_h_ or join [my server](https://discord.gg/ThBBAuueVJ).

---

Usage examples
===

Coming soon

---

Documentation:
===

---
`zhmiscellany_ocr.ocr()`
---

`zhmiscellany_ocr.ocr(image)`

Takes an image path or a PIL image object and runs local image text recognition and returns the text in the image. Does not use the internet to function.

#

`zhmiscellany_ocr.batch_ocr()`
---

`zhmiscellany_ocr.batch_ocr(images, threads=10, prints=False)`

Takes a list of image paths or PIL image objects and concurrently runs local image text recognition and returns the text in the image. Does not use the internet to function.

#