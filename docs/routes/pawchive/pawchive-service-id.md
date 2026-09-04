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
  "heat": 9,
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
      "description": "Posts of Ocn.(おしん⓲) from fanbox | Pawchive - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1216679953467047936",
      "image": "https://pawchive.pw/icons/fanbox/51075592",
      "ownerUserId": null,
      "siteUrl": "https://pawchive.pw/fanbox/user/51075592",
      "title": "Posts of Ocn.(おしん⓲) from fanbox | Pawchive",
      "type": "feed",
      "url": "rsshub://pawchive/fanbox/51075592"
    },
    {
      "description": "Posts of せるたす from fanbox | Pawchive - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1234181282800205824",
      "image": "https://pawchive.pw/icons/fanbox/37432797",
      "ownerUserId": null,
      "siteUrl": "https://pawchive.pw/fanbox/user/37432797",
      "title": "Posts of せるたす from fanbox | Pawchive",
      "type": "feed",
      "url": "rsshub://pawchive/fanbox/37432797"
    }
  ]
}
```
