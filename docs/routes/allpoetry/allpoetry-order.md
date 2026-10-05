# All Poetry - Poems

## Coverage
`index-only`

## Route
- Namespace: `allpoetry`
- Namespace Name: `All Poetry`
- Route Path: `/allpoetry/:order?`
- Route Name: `Poems`
- Example: `/allpoetry/newest`
- URL: `allpoetry.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `HenryQW`
- Source Location: `order.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `order`: Ordering, `newest`, `famous` or `picks`, `newest` by default


## Features
- `requirePuppeteer`: false
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/allpoetry/newest",
  "features": {
    "antiCrawler": true,
    "requirePuppeteer": false
  },
  "heat": 1,
  "location": "order.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "Poems",
  "parameters": {
    "order": "Ordering, `newest`, `famous` or `picks`, `newest` by default"
  },
  "path": "/:order?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "All Poetry - Newest - Powered by RSSHub",
      "errorAt": "2026-10-04T03:09:58.418Z",
      "errorMessage": "[GET] \"https://allpoetry.com/poems\": 403 Forbidden\n",
      "id": "1317111873757118464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://allpoetry.com/poems",
      "title": "All Poetry - Newest",
      "type": "feed",
      "url": "rsshub://allpoetry"
    }
  ]
}
```
