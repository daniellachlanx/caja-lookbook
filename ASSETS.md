# Asset structure — drag-and-drop convention

Every direction folder (`old-north/`, `newsprint/`, `high-key-sport/`) uses the **same
slot filenames**. To add or replace an asset, export it, rename it to the slot name,
and drop it in that direction's folder. The lookbook and any usage section reference
these exact paths, so a matching filename shows up automatically — no code changes.

## Canonical slots (per direction)

| Slot file | Checklist item | Notes |
|---|---|---|
| `lockup-horizontal.svg` | Horizontal lockup | symbol + wordmark, wide |
| `lockup-stacked.svg` | Stacked / vertical lockup | centred, tall |
| `wordmark.svg` / `.png` | Wordmark | the name in brand type |
| `symbol.svg` / `.png` | Primary symbol / brandmark | stands alone |
| `symbol-roundel.svg` | (symbol in a disc) | avatar / social variant |
| `monogram.svg` | Submark / monogram | single-letter reduction |
| `emblem.svg` / `.png` | Emblem / crest | symbol + text in one badge |
| `appicon.svg` | App icon / favicon source | full-bleed square |

## Colour variants (suffix on any slot)

| Suffix | Meaning |
|---|---|
| *(none)* | full-colour master — the source of truth |
| `-mono` | one-colour (solid black or one brand colour) |
| `-reversed` | knockout / light mark for dark backgrounds |
| `-transparent` | raster master with the background removed |

Example: `wordmark.png`, `wordmark-mono.svg`, `wordmark-reversed.svg`.

## Other folders

- `_raw/` (inside each direction) — original / unslotted source exports, kept for reference.
- Site icons live at the repo **root**: `favicon.svg`, `favicon-32.png`, `favicon-16.png`,
  `apple-touch-icon.png` (currently generated from Old North; regenerate if the chosen
  direction changes).

## How to add an asset

1. Export it (SVG preferred; transparent PNG for raster).
2. Rename to the slot name above (add a variant suffix if it's a colour variant).
3. Drop it into the direction folder, replacing any placeholder.
4. Update that folder's `README.md` status box if you like.

Each direction's `README.md` shows which slots are filled and which are still open.
