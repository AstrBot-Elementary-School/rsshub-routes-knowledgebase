# ALICESOFT - ニュース

## Coverage
`index-only`

## Route
- Namespace: `alicesoft`
- Namespace Name: `ALICESOFT`
- Route Path: `/alicesoft/information/:category?/:game?`
- Route Name: `ニュース`
- Example: `/alicesoft/information/game/cat377`
- URL: `www.alicesoft.com/information`
- Language: `_None_`
- Categories: `game`
- Maintainers: `keocheung`
- Source Location: `infomation.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category in the URL, which can be accessed under カテゴリ一覧 on the website.
- `game`: Game-specific subcategory in the URL, which can be accessed under カテゴリ一覧 on the website. In this case, the category value should be `game`.


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
  - `www.alicesoft.com/information`
  - `www.alicesoft.com/information/:category`
  - `www.alicesoft.com/information/:category/:game`
- `target`: `/information/:category/:game`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/alicesoft/information/game/cat377",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "infomation.ts",
  "maintainers": [
    "keocheung"
  ],
  "name": "ニュース",
  "parameters": {
    "category": "Category in the URL, which can be accessed under カテゴリ一覧 on the website.",
    "game": "Game-specific subcategory in the URL, which can be accessed under カテゴリ一覧 on the website. In this case, the category value should be `game`."
  },
  "path": "/information/:category?/:game?",
  "radar": [
    {
      "source": [
        "www.alicesoft.com/information",
        "www.alicesoft.com/information/:category",
        "www.alicesoft.com/information/:category/:game"
      ],
      "target": "/information/:category/:game"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(3) ] to not include 'https://www.alicesoft.com/escalationh…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "ALICESOFT 記事一覧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71404482934582272",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.alicesoft.com/information",
      "title": "ALICESOFT 記事一覧",
      "type": "feed",
      "url": "rsshub://alicesoft/information"
    },
    {
      "description": "ALICESOFT 超昂大戦の記事一覧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74007369916644352",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.alicesoft.com/information/game/cat377",
      "title": "ALICESOFT 超昂大戦の記事一覧",
      "type": "feed",
      "url": "rsshub://alicesoft/information/game/cat377"
    }
  ],
  "url": "www.alicesoft.com/information"
}
```
