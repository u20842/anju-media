# anju-media

Central photo library for Anju Redheendran's digital ecosystem (anjuredheendran.com, ICU-1111.com, BodySpeaks, Wikipedia/Wikidata, press kit, comp cards).

This repo provides permanent, public raw URLs for any image used across sites or shared with collaborators.

## Raw URL format

```
https://raw.githubusercontent.com/u20842/anju-media/main/[Category]/[Filename]
```

Example:
```
https://raw.githubusercontent.com/u20842/anju-media/main/Headshots/AR_Headshot_Studio_01.jpg
```

## Naming convention

```
AR_[Category]_[Description]_[Number].jpg
```

- `AR` — Anju Redheendran (constant prefix)
- `[Category]` — matches the album folder (Headshot, Portrait, FullBody, Editorial, Lifestyle, Performance)
- `[Description]` — short descriptor (e.g. PinkTop, StudioBW, DanceCostume)
- `[Number]` — two-digit sequence within that category (01, 02, 03...)

Example: `AR_Portrait_PinkTopHairDown_03.jpg`

## Album structure

| Folder | Status | Notes |
|---|---|---|
| `Headshots/` | ✅ Finalized (6 photos) | Professional headshots — speaking page, press kit |
| `Portraits/` | ✅ Finalized (7 photos) | Color portraits — homepage, about page |
| `Full Body/` | 🔲 To do | Full-length shots — modeling/lifestyle use |
| `Editorial/` | 🔲 To do | Styled/editorial shoot images |
| `Lifestyle/` | 🔲 To do | Candid/lifestyle imagery |
| `Performance/` | 🔲 To do | Dance, vocal, on-stage performance shots |

## Usage notes

- Keep this repo **public** so raw URLs work without authentication.
- B&W studio shots are designated for deeper pages (Speaking, etc.) — see master tracker for the specific unused shot numbers.
- Color portraits (black shirt look) are preferred for primary homepage hero placements; pink-shirt photos for secondary sections.
