# BruTown Cafe

Website for BruTown Cafe, 62/A Siddeswari Road, Dhaka. Live. Love. Eat.

A static site: `index.html` plus the images in `img/`. No build step.

## Run locally

```bash
python -m http.server 4173
```

Then open http://localhost:4173

## Deploy

Import the repo in Vercel with the framework preset set to "Other". No build command or output directory is needed.

## Editing

- Menu items and prices live in the `MENUS` object near the bottom of `index.html`.
- Opening hours appear in three places: the hours table, the open-now script, and the JSON-LD block in the head.
