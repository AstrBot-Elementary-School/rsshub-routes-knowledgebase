# Skebetter - Hot

## Coverage
`index-only`

## Route
- Namespace: `skebetter`
- Namespace Name: `Skebetter`
- Route Path: `/skebetter/:type`
- Route Name: `Hot`
- Example: `/skebetter/hot`
- URL: `skebetter.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `SnowAgar25`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 急上昇 | 週間 | 月間  | 新着   |
| ------ | ---- | ----- | ------ |
| hot    | week | month | latest |

## Parameters
- `type`: Type, see below


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
- `title`: `Skebetter - Hot`
- `source`:
  - `skebetter.com`
- `target`: `/hot`
### Rule 2
- `title`: `Skebetter - Week`
- `source`:
  - `skebetter.com`
- `target`: `/week`
### Rule 3
- `title`: `Skebetter - Month`
- `source`:
  - `skebetter.com`
- `target`: `/month`
### Rule 4
- `title`: `Skebetter - Latest`
- `source`:
  - `skebetter.com`
- `target`: `/latest`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "| 急上昇 | 週間 | 月間  | 新着   |\n| ------ | ---- | ----- | ------ |\n| hot    | week | month | latest |",
  "example": "/skebetter/hot",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 31,
  "location": "index.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "name": "Hot",
  "parameters": {
    "type": "Type, see below"
  },
  "path": "/:type",
  "radar": [
    {
      "source": [
        "skebetter.com"
      ],
      "target": "/hot",
      "title": "Skebetter - Hot"
    },
    {
      "source": [
        "skebetter.com"
      ],
      "target": "/week",
      "title": "Skebetter - Week"
    },
    {
      "source": [
        "skebetter.com"
      ],
      "target": "/month",
      "title": "Skebetter - Month"
    },
    {
      "source": [
        "skebetter.com"
      ],
      "target": "/latest",
      "title": "Skebetter - Latest"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Skebetter - 急上昇 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70009188313112576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://skebetter.com/",
      "title": "Skebetter - 急上昇",
      "type": "feed",
      "url": "rsshub://skebetter/hot"
    },
    {
      "description": "Skebetter - 新着 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "76931600411487232",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://skebetter.com/?term=latest",
      "title": "Skebetter - 新着",
      "type": "feed",
      "url": "rsshub://skebetter/latest"
    }
  ]
}
```
