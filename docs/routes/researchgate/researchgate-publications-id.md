# ResearchGate - Publications

## Coverage
`index-only`

## Route
- Namespace: `researchgate`
- Namespace Name: `ResearchGate`
- Route Path: `/researchgate/publications/:id`
- Route Name: `Publications`
- Example: `/researchgate/publications/Somsak-Panha`
- URL: `researchgate.net`
- Language: `_None_`
- Categories: `study`
- Maintainers: `nczitzk`
- Source Location: `publications.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Username, can be found in URL


## Features
- `requirePuppeteer`: true
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `researchgate.net/profile/:username`
- `target`: `/publications/:username`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/researchgate/publications/Somsak-Panha",
  "features": {
    "antiCrawler": true,
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "publications.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Publications",
  "parameters": {
    "id": "Username, can be found in URL"
  },
  "path": "/publications/:id",
  "radar": [
    {
      "source": [
        "researchgate.net/profile/:username"
      ],
      "target": "/publications/:username"
    }
  ],
  "topFeeds": []
}
```
