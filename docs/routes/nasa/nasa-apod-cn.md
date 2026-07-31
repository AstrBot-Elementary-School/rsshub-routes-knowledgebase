# NASA - NASA 中文

## Coverage
`index-only`

## Route
- Namespace: `nasa`
- Namespace Name: `NASA`
- Route Path: `/nasa/apod-cn`
- Route Name: `NASA 中文`
- Example: `/nasa/apod-cn`
- URL: `apod.nasa.govundefined`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `nczitzk, williamgateszhao`
- Source Location: `apod-cn.ts`
- Source Module: `_None_`

## Description
::: tip
[NASA 中文](https://www.nasachina.cn/) 提供了每日天文图的中英双语图文说明，但在更新上偶尔略有一两天的延迟。
:::

## Parameters
_None_


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
  - `apod.nasa.govundefined`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "::: tip\n[NASA 中文](https://www.nasachina.cn/) 提供了每日天文图的中英双语图文说明，但在更新上偶尔略有一两天的延迟。\n:::",
  "example": "/nasa/apod-cn",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1027,
  "location": "apod-cn.ts",
  "maintainers": [
    "nczitzk",
    "williamgateszhao"
  ],
  "name": "NASA 中文",
  "parameters": {},
  "path": "/apod-cn",
  "radar": [
    {
      "source": [
        "apod.nasa.govundefined"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "NASA中文 - 天文·每日一图 - Powered by RSSHub",
      "errorAt": "2026-07-07T18:05:29.879Z",
      "errorMessage": "[GET] \"https://www.nasachina.cn/wp-json/wp/v2/posts?categories=2&per_page=10\": 403 Forbidden\n[GET] \"https://www.nasachina.cn/wp-json/wp/v2/posts?categories=2&per_page=10\": 403 Forbidden\n[GET] \"https://www.nasachina.cn/wp-json/wp/v2/posts?categories=2&per_page=10\": 403 Forbidden\n[GET] \"https://www.nasachina.cn/wp-json/wp/v2/posts?categories=2&per_page=10\": 403 Forbidden\n[GET] \"https://www.nasachina.cn/wp-json/wp/v2/posts?categories=2&per_page=10\": 403 Forbidden\nAuthentication failed. Access denied.\n/nasa/apod-cn\nAuthentication failed. Access denied.\n/nasa/apod-cn\n[GET] \"https://www.nasachina.cn/wp-json/wp/v2/posts?categories=2&per_page=10\": 403 Forbidden\n503 \n[GET] \"https://www.nasachina.cn/wp-json/wp/v2/posts?categories=2&per_page=10\": 403 Forbidden\n[GET] \"https://www.nasachina.cn/wp-json/wp/v2/posts?categories=2&per_page=10\": 403 Forbidden\n",
      "id": "41857927240047616",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nasachina.cn/nasa-image-of-the-day",
      "title": "NASA中文 - 天文·每日一图",
      "type": "feed",
      "url": "rsshub://nasa/apod-cn"
    }
  ],
  "url": "apod.nasa.govundefined"
}
```
