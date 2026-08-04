# RSSHub - New routes

## Coverage
`index-only`

## Route
- Namespace: `rsshub`
- Namespace Name: `RSSHub`
- Route Path: `/rsshub/routes/:lang?`
- Route Name: `New routes`
- Example: `/rsshub/routes/en`
- URL: `docs.rsshub.app/*`
- Language: `_None_`
- Categories: `program-update, popular`
- Maintainers: `DIYgod`
- Source Location: `routes.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `lang`: {"default": "en", "description": "Language", "options": [{"label": "Chinese", "value": "zh"}, {"label": "English", "value": "en"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `docs.rsshub.app/*`
- `target`: `/routes`

## Raw JSON
```json
{
  "categories": [
    "program-update",
    "popular"
  ],
  "example": "/rsshub/routes/en",
  "heat": 4490,
  "location": "routes.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "New routes",
  "parameters": {
    "lang": {
      "default": "en",
      "description": "Language",
      "options": [
        {
          "label": "Chinese",
          "value": "zh"
        },
        {
          "label": "English",
          "value": "en"
        }
      ]
    }
  },
  "path": "/routes/:lang?",
  "radar": [
    {
      "source": [
        "docs.rsshub.app/*"
      ],
      "target": "/routes"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Everything is RSSible - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41147805276726402",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "RSSHub has new routes",
      "type": "feed",
      "url": "rsshub://rsshub/routes"
    },
    {
      "description": "万物皆可 RSS - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41425168656712704",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "RSSHub 有新路由啦",
      "type": "feed",
      "url": "rsshub://rsshub/routes/zh"
    }
  ],
  "url": "docs.rsshub.app/*",
  "view": 5
}
```
