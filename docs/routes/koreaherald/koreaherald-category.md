# The Korea Herald - News

## Coverage
`index-only`

## Route
- Namespace: `koreaherald`
- Namespace Name: `The Korea Herald`
- Route Path: `/koreaherald/:category{.+}?`
- Route Name: `News`
- Example: `/koreaherald/National`
- URL: `koreaherald.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
For example, the category for the page <https://www.koreaherald.com/Business> and <https://www.koreaherald.com/Business/Market> would be `/Business` and `/Business/Market` respectively.
:::

## Parameters
- `category`: Category from the path of the URL of the corresponding site, `National` by default


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
  - `www.koreaherald.com/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "::: tip\nFor example, the category for the page <https://www.koreaherald.com/Business> and <https://www.koreaherald.com/Business/Market> would be `/Business` and `/Business/Market` respectively.\n:::",
  "example": "/koreaherald/National",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 23,
  "location": "index.ts",
  "maintainers": [
    "quiniapiezoelectricity"
  ],
  "name": "News",
  "parameters": {
    "category": "Category from the path of the URL of the corresponding site, `National` by default"
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.koreaherald.com/:category"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "The Korea Herald - National - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "97091227879318528",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.koreaherald.com/National",
      "title": "The Korea Herald - National",
      "type": "feed",
      "url": "rsshub://koreaherald"
    },
    {
      "description": "The Korea Herald - National - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "97651779609807872",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.koreaherald.com/National",
      "title": "The Korea Herald - National",
      "type": "feed",
      "url": "rsshub://koreaherald/National"
    }
  ]
}
```
