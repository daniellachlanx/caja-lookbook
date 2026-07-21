# CAJA Interactive Lookbook

A brand-direction lookbook for CAJA (Carolina's American Judo), Matthews NC. It shows three complete design directions so the team can pick one to prototype for the website redesign.

## View

Live: https://daniellachlanx.github.io/caja-lookbook/

Or open `index.html` in any browser.

## The three directions

| Direction | Look | Voices |
|---|---|---|
| Old North | Collegiate athletic: cream, navy, athletic red, varsity type | Stadium, Varsity Block, Federation |
| Newsprint | Editorial black and white, one red accent | Swiss, Slab, Tabloid |
| High-Key Sport | Bright modern athletic: near-white, deep ink, electric blue | Studio, Performance, Power |

Each direction has a shared kit (logo, type, buttons, mobile), a homepage layout, and three voice treatments.

## Giving feedback

The star buttons are a browsing aid only. They are not recorded or shared, so pick your favorites, then send your top direction to [add channel] by [add deadline]. Recorded voting is on the to-do list below.

## Updating the site

Edit locally, then:

```
git add -A && git commit -m "message" && git push
```

GitHub Pages rebuilds in about a minute. `index.html` is self-contained apart from Google Fonts.

## Layout

```
index.html         the lookbook
ASSETS.md          the drag-and-drop asset convention (slot names per direction)
old-north/         Old North assets — consistent slot filenames + README manifest
newsprint/         Newsprint assets — same slot convention + README
high-key-sport/    High-Key Sport assets — same slot convention + README
favicon.svg …      site icons at root (favicon + apple-touch)
```

Each direction folder uses the **same slot filenames** so adding an asset is drag-and-drop
— see [`ASSETS.md`](ASSETS.md) and each folder's `README.md`.

**Build tracking:** [`checklist.html`](checklist.html) — the per-direction asset checklist
(what's done / partial / open). Open it in a browser and tick items as you build them.

## To do

- Fill in the one-line rationale under each direction
- Add photography (placeholders are intentional for now)
- Wire the transparent assets into the mockups
- Add recorded voting for the star favorites
