# DR (Danmarks Radio) - Nyheder

## Coverage
`index-only`

## Route
- Namespace: `dr`
- Namespace Name: `DR (Danmarks Radio)`
- Route Path: `/dr/:category?`
- Route Name: `Nyheder`
- Example: `/dr/senestenyt`
- URL: `dr.dk`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `cufezhusy`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
DRs nyheder, baseret på de officielle RSS-feeds. RSSHub forsøger at hente den fulde artikeltekst fra dr.dk. Hvis den fulde tekst ikke kan hentes, bruges beskrivelsen fra den officielle RSS-feed.

| Kategori   | Beskrivelse            |
| ---------- | ---------------------- |
| senestenyt | Seneste nyt (Kort nyt) |
| indland    | Indland                |
| udland     | Udland                 |
| penge      | Penge                  |
| politik    | Politik                |
| sporten    | Sport                  |
| viden      | Viden                  |

## Parameters
- `category`: {"description": "DR-sektion, se tabellen nedenfor. Standarden er `senestenyt` (Kort nyt)", "options": [{"label": "Seneste nyt (Kort nyt)", "value": "senestenyt"}, {"label": "Indland", "value": "indland"}, {"label": "Udland", "value": "udland"}, {"label": "Penge", "value": "penge"}, {"label": "Politik", "value": "politik"}, {"label": "Sport", "value": "sporten"}, {"label": "Viden", "value": "viden"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.dr.dk/nyheder`
- `target`: `/senestenyt`
### Rule 2
- `source`:
  - `www.dr.dk/nyheder/indland`
- `target`: `/indland`
### Rule 3
- `source`:
  - `www.dr.dk/nyheder/udland`
- `target`: `/udland`
### Rule 4
- `source`:
  - `www.dr.dk/nyheder/penge`
- `target`: `/penge`
### Rule 5
- `source`:
  - `www.dr.dk/nyheder/politik`
- `target`: `/politik`
### Rule 6
- `source`:
  - `www.dr.dk/sporten`
- `target`: `/sporten`
### Rule 7
- `source`:
  - `www.dr.dk/nyheder/viden`
- `target`: `/viden`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "DRs nyheder, baseret på de officielle RSS-feeds. RSSHub forsøger at hente den fulde artikeltekst fra dr.dk. Hvis den fulde tekst ikke kan hentes, bruges beskrivelsen fra den officielle RSS-feed.\n\n| Kategori   | Beskrivelse            |\n| ---------- | ---------------------- |\n| senestenyt | Seneste nyt (Kort nyt) |\n| indland    | Indland                |\n| udland     | Udland                 |\n| penge      | Penge                  |\n| politik    | Politik                |\n| sporten    | Sport                  |\n| viden      | Viden                  |",
  "example": "/dr/senestenyt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "cufezhusy"
  ],
  "name": "Nyheder",
  "parameters": {
    "category": {
      "description": "DR-sektion, se tabellen nedenfor. Standarden er `senestenyt` (Kort nyt)",
      "options": [
        {
          "label": "Seneste nyt (Kort nyt)",
          "value": "senestenyt"
        },
        {
          "label": "Indland",
          "value": "indland"
        },
        {
          "label": "Udland",
          "value": "udland"
        },
        {
          "label": "Penge",
          "value": "penge"
        },
        {
          "label": "Politik",
          "value": "politik"
        },
        {
          "label": "Sport",
          "value": "sporten"
        },
        {
          "label": "Viden",
          "value": "viden"
        }
      ]
    }
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.dr.dk/nyheder"
      ],
      "target": "/senestenyt"
    },
    {
      "source": [
        "www.dr.dk/nyheder/indland"
      ],
      "target": "/indland"
    },
    {
      "source": [
        "www.dr.dk/nyheder/udland"
      ],
      "target": "/udland"
    },
    {
      "source": [
        "www.dr.dk/nyheder/penge"
      ],
      "target": "/penge"
    },
    {
      "source": [
        "www.dr.dk/nyheder/politik"
      ],
      "target": "/politik"
    },
    {
      "source": [
        "www.dr.dk/sporten"
      ],
      "target": "/sporten"
    },
    {
      "source": [
        "www.dr.dk/nyheder/viden"
      ],
      "target": "/viden"
    }
  ],
  "topFeeds": []
}
```
