# TRACYHAYES · image assets

Artwork drop for the **Real Estate Excellence** rebuild.
Live build: https://marshall.readtomato.com/thp2026/

Upload files to the root of this repo using the exact filenames below. The build
script reads them by name, so a correct filename means zero code changes on my end.

---

## How to use this

1. Drop the file in with the exact name from the tables below.
2. Anything not ready yet, just skip. The site shows a striped placeholder that
   labels its own pixel size on screen, so you can always re-check in the browser.
3. Ping me when a batch lands and I'll pull them into the build.

**Format:** WebP for photography, quality ~78. SVG for the logo.
**Sizes below are export sizes.** They are already 2× for retina. Build to those numbers.

---

## 1 · Logo (5 files)

One horizontal lockup, roughly 6.5:1. **Convert all type to outlines.** External
SVGs can't load webfonts, so live text falls back and breaks the lockup.

| Filename | Size | Notes |
|---|---|---|
| `THP-LOGO-LIGHT.svg` | 392 × 60 artboard | bone version, sits on near-black. used in header and footer |
| `THP-LOGO-DARK.svg` | 392 × 60 artboard | ink version, same lockup, for light sections |
| `THP-LOGO-LIGHT-2X.png` | 556 × 86 | raster fallback |
| `THP-FAVICON.png` | 512 × 512 | square mark only, no wordmark |
| `THP-OG-CARD.jpg` | 1200 × 630 | link-preview card for social shares |

Clear space around the lockup: equal to the height of the mark on all sides.

---

## 2 · Page heroes (5 files)

| Filename | Size | Page |
|---|---|---|
| `THP-HERO-WATCH.webp` | 1384 × 1200 | watch |
| `THP-HERO-ABOUT.webp` | 1384 × 1200 | about |
| `THP-HERO-BE-A-GUEST.webp` | 1384 × 1200 | be a guest |
| `THP-HERO-EPISODES.webp` | 1036 × 1338 | episodes index (narrower, taller column) |
| `THP-HERO-GUESTS.webp` | 1036 × 1338 | guests index (narrower, taller column) |

---

## 3 · Full-bleed banners (3 files)

These span the whole viewport. Keep the important content in the **middle 1440 px**.
The edges get cropped on narrow screens. Cut at 3840 wide if they need to hold up
on ultrawide monitors.

| Filename | Size | Where |
|---|---|---|
| `THP-BANNER-BE-A-GUEST.webp` | 2880 × 988 | foot of most pages |
| `THP-BANNER-THE-BRIEF.webp` | 2880 × 664 | home page |
| `THP-BANNER-NOMINATE.webp` | 2880 × 634 | be-a-guest page, sits behind the form |

---

## 4 · Section features (2 files)

| Filename | Size | Section |
|---|---|---|
| `THP-FEATURE-BROWSE-BY-BEAT.webp` | 1242 × 660 | Browse by beat |
| `THP-FEATURE-KNOW-YOUR-FARM-AREA.webp` | 1242 × 660 | Know your farm area |

---

## 5 · Beats (7 files)

**One photo each, 1600 × 1200.** I crop it two ways in CSS. Wide for the tile on
the index, tall for the hero on the hub page. That's why it's one file instead of two.

| Filename | Beat |
|---|---|
| `THP-BEAT-LENDING-TITLE.webp` | lending + title |
| `THP-BEAT-MARKET-DATA.webp` | market data |
| `THP-BEAT-MARKETING-LEADGEN.webp` | marketing + lead gen |
| `THP-BEAT-MILITARY-RELOCATION.webp` | military relocation |
| `THP-BEAT-MINDSET.webp` | mindset |
| `THP-BEAT-NEW-CONSTRUCTION.webp` | new construction |
| `THP-BEAT-TEAMS-LEADERSHIP.webp` | teams + leadership |

---

## 6 · Markets (13 files)

**One photo each, 1600 × 1200.** Same two-crop treatment as the beats.

| Filename | Market |
|---|---|
| `THP-MARKET-AMELIA.webp` | Amelia Island |
| `THP-MARKET-CLAY-COUNTY.webp` | Clay County |
| `THP-MARKET-EAGLE-HARBOR.webp` | Eagle Harbor |
| `THP-MARKET-FLEMING-ISLAND.webp` | Fleming Island |
| `THP-MARKET-JACKSONVILLE.webp` | Jacksonville |
| `THP-MARKET-NAS-JACKSONVILLE.webp` | NAS Jacksonville |
| `THP-MARKET-NOCATEE.webp` | Nocatee |
| `THP-MARKET-ORANGE-PARK.webp` | Orange Park |
| `THP-MARKET-PONTE-VEDRA.webp` | Ponte Vedra |
| `THP-MARKET-RIVERTOWN.webp` | RiverTown |
| `THP-MARKET-ST-AUGUSTINE.webp` | St. Augustine |
| `THP-MARKET-ST-JOHNS.webp` | St. Johns County |
| `THP-MARKET-THE-VILLAGES.webp` | The Villages |

---

## 7 · Missing guest portraits (4 files, optional)

Four guests have no photo anywhere, not on their profile and not in the episode art.
They currently show a striped block. If you can source them:

`THP-GUEST-<FIRSTNAME>-<LASTNAME>.webp` at **434 × 578** (3:4, head near the top).

---

## Rules that apply to every image

- **Heads sit high.** Every portrait crop is anchored 8 to 10% from the top edge,
  because the source photography is head-weighted. Leave headroom. Never centre a
  face vertically in the frame.
- **No overlays, ever.** Nothing goes on top of a photograph. No scrims, tints, or
  gradients. Text always sits in a panel beside the image. Deliver photography clean.
- **Cropping is `object-fit: cover`.** The image fills the box and the overflow is
  trimmed. Keep the subject inside the middle two-thirds horizontally.
- **Grounds.** Most sections are near-black `#0A0B0C` or petrol `#0E3B3E`. Episode
  and transcript sections are bone `#EDEBE3`. The accent is `#C24A17`.

---

## Count

| | |
|---|---|
| Logo files | 5 |
| Page heroes | 5 |
| Full-bleed banners | 3 |
| Section features | 2 |
| Beats | 7 |
| Markets | 13 |
| **Total to supply** | **35** |
| Missing guest portraits (optional) | 4 |

Everything else on the site (312 episode covers, 223 guest portraits, 47 vertical
videos) is already populated from the existing feed and needs nothing.
