# Castanet - News

## Coverage
`index-only`

## Route
- Namespace: `castanet`
- Namespace Name: `Castanet`
- Route Path: `/castanet/:category?`
- Route Name: `News`
- Example: `/castanet/Kelowna`
- URL: `www.castanet.net`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"default": "Recent Headlines", "description": "Category", "options": [{"label": "Top Headlines", "value": "Top Headlines"}, {"label": "Recent Headlines", "value": "Recent Headlines"}, {"label": "Kelowna", "value": "Kelowna"}, {"label": "West-Kelowna", "value": "West-Kelowna"}, {"label": "Peachland", "value": "Peachland"}, {"label": "Vernon", "value": "Vernon"}, {"label": "Salmon-Arm", "value": "Salmon-Arm"}, {"label": "Penticton", "value": "Penticton"}, {"label": "Oliver-Osoyoos", "value": "Oliver-Osoyoos"}, {"label": "Kamloops", "value": "Kamloops"}, {"label": "Nelson", "value": "Nelson"}, {"label": "BC", "value": "BC"}, {"label": "Canada", "value": "Canada"}, {"label": "World", "value": "World"}, {"label": "Business", "value": "Business"}, {"label": "Sports", "value": "Sports"}, {"label": "ShowBiz", "value": "ShowBiz"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.castanet.net/news/:category/`
- `target`: `/:category`
### Rule 2
- `source`:
  - `www.castanet.net/`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/castanet/Kelowna",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "News",
  "parameters": {
    "category": {
      "default": "Recent Headlines",
      "description": "Category",
      "options": [
        {
          "label": "Top Headlines",
          "value": "Top Headlines"
        },
        {
          "label": "Recent Headlines",
          "value": "Recent Headlines"
        },
        {
          "label": "Kelowna",
          "value": "Kelowna"
        },
        {
          "label": "West-Kelowna",
          "value": "West-Kelowna"
        },
        {
          "label": "Peachland",
          "value": "Peachland"
        },
        {
          "label": "Vernon",
          "value": "Vernon"
        },
        {
          "label": "Salmon-Arm",
          "value": "Salmon-Arm"
        },
        {
          "label": "Penticton",
          "value": "Penticton"
        },
        {
          "label": "Oliver-Osoyoos",
          "value": "Oliver-Osoyoos"
        },
        {
          "label": "Kamloops",
          "value": "Kamloops"
        },
        {
          "label": "Nelson",
          "value": "Nelson"
        },
        {
          "label": "BC",
          "value": "BC"
        },
        {
          "label": "Canada",
          "value": "Canada"
        },
        {
          "label": "World",
          "value": "World"
        },
        {
          "label": "Business",
          "value": "Business"
        },
        {
          "label": "Sports",
          "value": "Sports"
        },
        {
          "label": "ShowBiz",
          "value": "ShowBiz"
        }
      ]
    }
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.castanet.net/news/:category/"
      ],
      "target": "/:category"
    },
    {
      "source": [
        "www.castanet.net/"
      ],
      "target": "/"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.castanet.net"
}
```
