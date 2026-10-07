# Financial Mathematics for Actuaries — a textbook rewrite

This project is an independent rewrite and expansion of the NPTEL IIT Madras course
[Financial Mathematics for Actuaries](https://nptel.ac.in/courses/111106930).
The [YouTube playlist](https://www.youtube.com/playlist?list=PLFym2Tj7eXgo)
serves as the spine: it sets the topic sequence and provides timestamped anchors.

The 58 recordings (26.8 hours) are grouped into 17 topic chapters. Five lab and five review
recordings supply exercises. Around the spine, each chapter adds original explanations,
derivations, runnable Python checks and worked problems. Source maps separate lecture
material, research extensions and original teaching constructions.

**Status: in progress.** The reader shell is published first. Each chapter is added after
independent review and local validation. Open `index.html` to read; the reader works offline.

```sh
python build_book.py
python validate_books.py --browser
```
