# musify - Latest

## Coverage
`index-only`

## Route
- Namespace: `musify`
- Namespace Name: `musify`
- Route Path: `/musify/:language?`
- Route Name: `Latest`
- Example: `/musify/en`
- URL: `musify.club`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
To subscribe to [Latest](https://musify.club/en), where the source URL is `https://musify.club/en`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/musify/en`](https://rsshub.app/musify/en).
:::

## Parameters
- `category`: {"description": "Language, Russian by default", "options": [{"label": "Russian", "value": ""}, {"label": "English", "value": "en"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `musify.club/:language`
- `target`: `/:language`
### Rule 2
- `title`: `Latest`
- `source`:
  - `musify.club/en`
- `target`: `/en`
### Rule 3
- `title`: `​​Последняя`
- `source`:
  - `musify.club`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\nTo subscribe to [Latest](https://musify.club/en), where the source URL is `https://musify.club/en`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/musify/en`](https://rsshub.app/musify/en).\n:::",
  "example": "/musify/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 2,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Latest",
  "parameters": {
    "category": {
      "description": "Language, Russian by default",
      "options": [
        {
          "label": "Russian",
          "value": ""
        },
        {
          "label": "English",
          "value": "en"
        }
      ]
    }
  },
  "path": "/:language?",
  "radar": [
    {
      "source": [
        "musify.club/:language"
      ],
      "target": "/:language"
    },
    {
      "source": [
        "musify.club/en"
      ],
      "target": "/en",
      "title": "Latest"
    },
    {
      "source": [
        "musify.club"
      ],
      "target": "/",
      "title": "​​Последняя"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Проверка браузера… - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "164874302196685824",
      "image": "https://s.musify.club/images/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://musify.club/en",
      "title": "Проверка браузера…",
      "type": "feed",
      "url": "rsshub://musify/en"
    },
    {
      "description": "Проверка браузера… - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "165777653595388928",
      "image": "https://s.musify.club/images/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://musify.club/",
      "title": "Проверка браузера…",
      "type": "feed",
      "url": "rsshub://musify"
    }
  ],
  "url": "musify.club",
  "view": 0
}
```
