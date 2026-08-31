# Gamer Secret - Category

## Coverage
`index-only`

## Route
- Namespace: `gamersecret`
- Namespace Name: `Gamer Secret`
- Route Path: `/gamersecret/:type?/:category?`
- Route Name: `Category`
- Example: `/gamersecret`
- URL: `gamersecret.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| Latest News | PC | Playstation | Nintendo | Xbox | Moblie |
| ----------- | -- | ----------- | -------- | ---- | ------ |
| latest-news | pc | playstation | nintendo | xbox | moblie |

Or

| GENERAL          | GENERAL EN         | MOBILE          | MOBILE EN         |
| ---------------- | ------------------ | --------------- | ----------------- |
| category/general | category/generalen | category/mobile | category/mobileen |

| NINTENDO          | NINTENDO EN         | PC          | PC EN         |
| ----------------- | ------------------- | ----------- | ------------- |
| category/nintendo | category/nintendoen | category/pc | category/pcen |

| PLAYSTATION          | PLAYSTATION EN         | REVIEWS          |
| -------------------- | ---------------------- | ---------------- |
| category/playstation | category/playstationen | category/reviews |

| XBOX          | XBOX EN         |
| ------------- | --------------- |
| category/xbox | category/xboxen |

## Parameters
- `type`: Type, see below, Latest News by default
- `category`: Category, see below


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
  - `gamersecret.com/:type`
  - `gamersecret.com/:type/:category`
  - `gamersecret.com/`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| Latest News | PC | Playstation | Nintendo | Xbox | Moblie |\n| ----------- | -- | ----------- | -------- | ---- | ------ |\n| latest-news | pc | playstation | nintendo | xbox | moblie |\n\nOr\n\n| GENERAL          | GENERAL EN         | MOBILE          | MOBILE EN         |\n| ---------------- | ------------------ | --------------- | ----------------- |\n| category/general | category/generalen | category/mobile | category/mobileen |\n\n| NINTENDO          | NINTENDO EN         | PC          | PC EN         |\n| ----------------- | ------------------- | ----------- | ------------- |\n| category/nintendo | category/nintendoen | category/pc | category/pcen |\n\n| PLAYSTATION          | PLAYSTATION EN         | REVIEWS          |\n| -------------------- | ---------------------- | ---------------- |\n| category/playstation | category/playstationen | category/reviews |\n\n| XBOX          | XBOX EN         |\n| ------------- | --------------- |\n| category/xbox | category/xboxen |",
  "example": "/gamersecret",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Category",
  "parameters": {
    "category": "Category, see below",
    "type": "Type, see below, Latest News by default"
  },
  "path": "/:type?/:category?",
  "radar": [
    {
      "source": [
        "gamersecret.com/:type",
        "gamersecret.com/:type/:category",
        "gamersecret.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
