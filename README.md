# Rome Brief

Public weekend briefing for a stay in Rome, 26–29 November 2026 (Hotel Madison, Via Marsala 60).

- Live site: https://oskarwkarlsson.github.io/rome-brief/
- Repository: https://github.com/oskarwkarlsson/rome-brief

The site is a single static `index.html` at the root of `main`, published with GitHub Pages. Update it morning and evening by editing that file, committing, and pushing.

## Update (from this repo)

```bash
cd /workspace/rome-brief
# edit index.html — refresh the "Last updated" stamp in Europe/Rome (CET)
git add index.html
git commit -m "Evening brief, DD Mon 2026"
git push origin main
```

Pages usually rebuild within a minute or two. The live URL is the same after every push.

Local copy lives at `/workspace/rome-brief` (keep it here; do not use a `dist` or `build` folder).

Only publish hours, prices and event listings that have been checked against official or venue pages the same day. Link the sources at the bottom of the page.
