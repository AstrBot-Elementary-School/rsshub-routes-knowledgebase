# Pawchive - Posts

## Coverage
`index-only`

## Route
- Namespace: `pawchive`
- Namespace Name: `Pawchive`
- Route Path: `/pawchive/:service/:id`
- Route Name: `Posts`
- Example: `/pawchive/fanbox/22445`
- URL: `pawchive.pw`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `TonyRL`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `service`: service, either `patreon` or `fanbox`
- `id`: User id, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `pawchive.pw/`
- `target`: ``
### Rule 2
- `source`:
  - `pawchive.pw/:service/user/:id`
- `target`: `/:service/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/pawchive/fanbox/22445",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 21,
  "location": "index.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Posts",
  "parameters": {
    "id": "User id, can be found in URL",
    "service": "service, either `patreon` or `fanbox`"
  },
  "path": "/:service/:id",
  "radar": [
    {
      "source": [
        "pawchive.pw/"
      ],
      "target": ""
    },
    {
      "source": [
        "pawchive.pw/:service/user/:id"
      ],
      "target": "/:service/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Posts of Old Apple from patreon | Pawchive - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1304085459994804224",
      "image": "https://pawchive.pw/icons/patreon/66342169",
      "ownerUserId": null,
      "siteUrl": "https://pawchive.pw/patreon/user/66342169",
      "title": "Posts of Old Apple from patreon | Pawchive",
      "type": "feed",
      "url": "rsshub://pawchive/patreon/66342169"
    },
    {
      "description": "Posts of JK君 from fanbox | Pawchive - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1300759803315748864",
      "image": "https://pawchive.pw/icons/fanbox/25877697",
      "ownerUserId": null,
      "siteUrl": "https://pawchive.pw/fanbox/user/25877697",
      "title": "Posts of JK君 from fanbox | Pawchive",
      "type": "feed",
      "url": "rsshub://pawchive/fanbox/25877697"
    }
  ]
}
```
