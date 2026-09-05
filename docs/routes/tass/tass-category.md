# Russian News Agency TASS - News

## Coverage
`index-only`

## Route
- Namespace: `tass`
- Namespace Name: `Russian News Agency TASS`
- Route Path: `/tass/:category?`
- Route Name: `News`
- Example: `/tass/politics`
- URL: `tass.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| Russian Politics & Diplomacy | World | Business & Economy | Military & Defense | Science & Space | Emergencies | Society & Culture | Press Review | Sports |
| ---------------------------- | ----- | ------------------ | ------------------ | --------------- | ----------- | ----------------- | ------------ | ------ |
| politics                     | world | economy            | defense            | science         | emergencies | society           | pressreview  | sports |

## Parameters
- `category`: Category, can be found in URL, `politics` by default


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
  - `tass.com/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| Russian Politics & Diplomacy | World | Business & Economy | Military & Defense | Science & Space | Emergencies | Society & Culture | Press Review | Sports |\n| ---------------------------- | ----- | ------------------ | ------------------ | --------------- | ----------- | ----------------- | ------------ | ------ |\n| politics                     | world | economy            | defense            | science         | emergencies | society           | pressreview  | sports |",
  "example": "/tass/politics",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 85,
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "News",
  "parameters": {
    "category": "Category, can be found in URL, `politics` by default"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "tass.com/:category"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Russian Politics & Diplomacy - TASS - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64310795153576960",
      "image": "https://tass.com/img/blocks/common/tass_logo_share_eng.png",
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "Russian Politics & Diplomacy - TASS",
      "type": "feed",
      "url": "rsshub://tass/politics"
    },
    {
      "description": "World - TASS - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64311310991740928",
      "image": "https://tass.com/img/blocks/common/tass_logo_share_eng.png",
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "World - TASS",
      "type": "feed",
      "url": "rsshub://tass/world"
    }
  ]
}
```
