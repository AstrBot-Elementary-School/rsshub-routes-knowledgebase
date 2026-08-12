# kpopping - Pics

## Coverage
`index-only`

## Route
- Namespace: `kpopping`
- Namespace Name: `kpopping`
- Route Path: `/kpopping/kpics/:filter{.+}?`
- Route Name: `Pics`
- Example: `/kpopping/kpics/gender-male/category-all/idol-any/group-any/order`
- URL: `kpopping.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `nczitzk`
- Source Location: `kpics.ts`
- Source Module: `_None_`

## Description
::: tip
If you subscribe to [All male photo albums](https://kpopping.com/kpics/gender-male/category-all/idol-any/group-any/order)，where the URL is `https://kpopping.com/kpics/gender-male/category-all/idol-any/group-any/order`, extract the part `https://kpopping.com/kpics/` to the end, which is `gender-male/category-all/idol-any/group-any/order`, and use it as the parameter to fill in. Therefore, the route will be [`/kpopping/kpics/gender-male/category-all/idol-any/group-any/order`](https://rsshub.app/kpopping/kpics/gender-male/category-all/idol-any/group-any/order).
:::

## Parameters
- `filter`: Filter


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
  - `kpopping.com/kpics/:filter`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "::: tip\nIf you subscribe to [All male photo albums](https://kpopping.com/kpics/gender-male/category-all/idol-any/group-any/order)，where the URL is `https://kpopping.com/kpics/gender-male/category-all/idol-any/group-any/order`, extract the part `https://kpopping.com/kpics/` to the end, which is `gender-male/category-all/idol-any/group-any/order`, and use it as the parameter to fill in. Therefore, the route will be [`/kpopping/kpics/gender-male/category-all/idol-any/group-any/order`](https://rsshub.app/kpopping/kpics/gender-male/category-all/idol-any/group-any/order).\n:::",
  "example": "/kpopping/kpics/gender-male/category-all/idol-any/group-any/order",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 39,
  "location": "kpics.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Pics",
  "parameters": {
    "filter": "Filter"
  },
  "path": "/kpics/:filter{.+}?",
  "radar": [
    {
      "source": [
        "kpopping.com/kpics/:filter"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Browse thousands of high quality K-pop photos. Concept photos, teasers, photoshoots, and more. - Powered by RSSHub",
      "errorAt": "2026-04-28T03:43:04.263Z",
      "errorMessage": "[GET] \"https://kpopping.com/kpics/gender-female/category-all/idol-any/group-any/order\": 410 Gone\n[GET] \"https://kpopping.com/kpics/gender-female/category-all/idol-any/group-any/order\": 410 Gone\n[GET] \"https://kpopping.com/kpics/gender-female/category-all/idol-any/group-any/order\": 410 Gone\n",
      "id": "127912538951825408",
      "image": "https://kpopping.com/build/images/kpopping-default-detailed.jpg",
      "ownerUserId": null,
      "siteUrl": "https://kpopping.com/kpics/gender-female/category-all/idol-any/group-any/order",
      "title": "HQ K-pop Photos — Concept Photos, Teasers & Photoshoots (2026) | kpopping",
      "type": "feed",
      "url": "rsshub://kpopping/kpics/gender-female/category-all/idol-any/group-any/order"
    },
    {
      "description": "Browse thousands of high quality Kpop photos. Concept photos, teasers, photoshoots, and more. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "160056537743224832",
      "image": "https://kpopping.com/build/images/kpopping-default-detailed.jpg",
      "ownerUserId": null,
      "siteUrl": "https://kpopping.com/kpics",
      "title": "HQ Kpop Photos — Concept Photos, Teasers & Photoshoots (2026) | kpopping",
      "type": "feed",
      "url": "rsshub://kpopping/kpics"
    }
  ],
  "url": "kpopping.com",
  "view": 0,
  "zh": {
    "description": "::: tip\n若订阅 [All male photo albums](https://kpopping.com/kpics/gender-male/category-all/idol-any/group-any/order)，网址为 `https://kpopping.com/kpics/gender-male/category-all/idol-any/group-any/order`，请截取 `https://kpopping.com/kpics/` 到末尾的部分 `gender-male/category-all/idol-any/group-any/order` 作为 `filter` 参数填入，此时目标路由为 [`/kpopping/kpics/gender-male/category-all/idol-any/group-any/order`](https://rsshub.app/kpopping/kpics/gender-male/category-all/idol-any/group-any/order)。\n:::",
    "name": "Pics",
    "parameters": {
      "filter": "筛选，可在对应分类页 URL 中找到"
    }
  }
}
```
