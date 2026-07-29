# The Washington Post - App

## Coverage
`index-only`

## Route
- Namespace: `washingtonpost`
- Namespace Name: `The Washington Post`
- Route Path: `/washingtonpost/app/:category{.+}?`
- Route Name: `App`
- Example: `/washingtonpost/app/national`
- URL: `www.washingtonpost.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `app.tsx`
- Source Module: `_None_`

## Description
::: tip
For example, the category for <https://www.washingtonpost.com/national/investigations> would be /national/investigations.
:::

## Parameters
- `category`: Category from the path of the URL of the corresponding site, see below


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.washingtonpost.com/:category`
- `target`: `/app/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "::: tip\nFor example, the category for <https://www.washingtonpost.com/national/investigations> would be /national/investigations.\n:::",
  "example": "/washingtonpost/app/national",
  "features": {
    "antiCrawler": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 301,
  "location": "app.tsx",
  "maintainers": [
    "quiniapiezoelectricity"
  ],
  "name": "App",
  "parameters": {
    "category": "Category from the path of the URL of the corresponding site, see below"
  },
  "path": "/app/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.washingtonpost.com/:category"
      ],
      "target": "/app/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "The Washington Post - World - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "86963096699402240",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://washingtonpost.com/world/",
      "title": "The Washington Post - World",
      "type": "feed",
      "url": "rsshub://washingtonpost/app/world"
    },
    {
      "description": "The Washington Post - Breaking news and latest headlines, U.S. news, world news, and video - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74046907703950336",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://washingtonpost.com/",
      "title": "The Washington Post - Breaking news and latest headlines, U.S. news, world news, and video",
      "type": "feed",
      "url": "rsshub://washingtonpost/app"
    }
  ]
}
```
