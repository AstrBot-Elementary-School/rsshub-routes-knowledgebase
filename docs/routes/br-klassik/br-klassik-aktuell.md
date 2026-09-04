# BR-Klassik - Aktuell (News & Kritik)

## Coverage
`index-only`

## Route
- Namespace: `br-klassik`
- Namespace Name: `BR-Klassik`
- Route Path: `/br-klassik/aktuell`
- Route Name: `Aktuell (News & Kritik)`
- Example: `/br-klassik/aktuell`
- URL: `br-klassik.de`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `wongJG`
- Source Location: `aktuell.ts`
- Source Module: `_None_`

## Description
News und Kritik aus der Welt der Klassischen Musik.

## Parameters
_None_


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `requireConfig`: false

## Radar
### Rule 1
- `source`:
  - `www.br-klassik.de/aktuell/index.html`
- `target`: `/aktuell`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "News und Kritik aus der Welt der Klassischen Musik.",
  "example": "/br-klassik/aktuell",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "aktuell.ts",
  "maintainers": [
    "wongJG"
  ],
  "name": "Aktuell (News & Kritik)",
  "parameters": {},
  "path": "/aktuell",
  "radar": [
    {
      "source": [
        "www.br-klassik.de/aktuell/index.html"
      ],
      "target": "/aktuell"
    }
  ],
  "topFeeds": []
}
```
