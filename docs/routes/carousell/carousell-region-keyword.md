# Carousell - Keyword Search

## Coverage
`index-only`

## Route
- Namespace: `carousell`
- Namespace Name: `Carousell`
- Route Path: `/carousell/:region/:keyword`
- Route Name: `Keyword Search`
- Example: `/carousell/sg/iphone`
- URL: `carousell.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `region`: {"description": "Region code", "options": [{"label": "Australia", "value": "au"}, {"label": "Canada", "value": "ca"}, {"label": "Hong Kong", "value": "hk"}, {"label": "Indonesia", "value": "id"}, {"label": "Malaysia", "value": "my"}, {"label": "New Zealand", "value": "nz"}, {"label": "Philippines", "value": "ph"}, {"label": "Singapore", "value": "sg"}, {"label": "Taiwan", "value": "tw"}]}
- `keyword`: {"description": "Search keyword"}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `au.carousell.com/search/:keyword`
- `target`: `/au/:keyword`
### Rule 2
- `source`:
  - `ca.carousell.com/search/:keyword`
- `target`: `/ca/:keyword`
### Rule 3
- `source`:
  - `www.carousell.com.hk/search/:keyword`
- `target`: `/hk/:keyword`
### Rule 4
- `source`:
  - `id.carousell.com/search/:keyword`
- `target`: `/id/:keyword`
### Rule 5
- `source`:
  - `www.carousell.com.my/search/:keyword`
- `target`: `/my/:keyword`
### Rule 6
- `source`:
  - `nz.carousell.com/search/:keyword`
- `target`: `/nz/:keyword`
### Rule 7
- `source`:
  - `www.carousell.ph/search/:keyword`
- `target`: `/ph/:keyword`
### Rule 8
- `source`:
  - `www.carousell.sg/search/:keyword`
- `target`: `/sg/:keyword`
### Rule 9
- `source`:
  - `tw.carousell.com/search/:keyword`
- `target`: `/tw/:keyword`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/carousell/sg/iphone",
  "heat": 4,
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Keyword Search",
  "parameters": {
    "keyword": {
      "description": "Search keyword"
    },
    "region": {
      "description": "Region code",
      "options": [
        {
          "label": "Australia",
          "value": "au"
        },
        {
          "label": "Canada",
          "value": "ca"
        },
        {
          "label": "Hong Kong",
          "value": "hk"
        },
        {
          "label": "Indonesia",
          "value": "id"
        },
        {
          "label": "Malaysia",
          "value": "my"
        },
        {
          "label": "New Zealand",
          "value": "nz"
        },
        {
          "label": "Philippines",
          "value": "ph"
        },
        {
          "label": "Singapore",
          "value": "sg"
        },
        {
          "label": "Taiwan",
          "value": "tw"
        }
      ]
    }
  },
  "path": "/:region/:keyword",
  "radar": [
    {
      "source": [
        "au.carousell.com/search/:keyword"
      ],
      "target": "/au/:keyword"
    },
    {
      "source": [
        "ca.carousell.com/search/:keyword"
      ],
      "target": "/ca/:keyword"
    },
    {
      "source": [
        "www.carousell.com.hk/search/:keyword"
      ],
      "target": "/hk/:keyword"
    },
    {
      "source": [
        "id.carousell.com/search/:keyword"
      ],
      "target": "/id/:keyword"
    },
    {
      "source": [
        "www.carousell.com.my/search/:keyword"
      ],
      "target": "/my/:keyword"
    },
    {
      "source": [
        "nz.carousell.com/search/:keyword"
      ],
      "target": "/nz/:keyword"
    },
    {
      "source": [
        "www.carousell.ph/search/:keyword"
      ],
      "target": "/ph/:keyword"
    },
    {
      "source": [
        "www.carousell.sg/search/:keyword"
      ],
      "target": "/sg/:keyword"
    },
    {
      "source": [
        "tw.carousell.com/search/:keyword"
      ],
      "target": "/tw/:keyword"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Carousell SG Search - GPU - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1158145898106978304",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "Carousell SG Search - GPU",
      "type": "feed",
      "url": "rsshub://carousell/sg/GPU"
    },
    {
      "description": "Carousell SG Search - RAM - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1182663805922836480",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "Carousell SG Search - RAM",
      "type": "feed",
      "url": "rsshub://carousell/sg/RAM"
    }
  ]
}
```
