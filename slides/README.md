# Slides

One Slidev deck per week, `week01.md` through `week13.md`. Shared look in `style.css`: white background for projectors, blue and amber accents.

Run one deck:

```bash
slidev week01.md
```

Export to PDF (needs `npm i -g playwright-chromium`, done Sept 7, 2026):

```bash
slidev export week01.md --output week01.pdf
```

Slidev and the Seriph theme are installed globally; there is no `package.json` here on purpose.
