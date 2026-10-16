# 巴伦周刊中文版 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `barronschina`
- Namespace Name: `巴伦周刊中文版`
- Route Path: `/barronschina/:id?`
- Route Name: `栏目`
- Example: `/barronschina`
- URL: `www.barrons.com.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
栏目 id 留空则返回快报，可在新站栏目地址 `https://www.barrons.com.cn/column/121` 中找到栏目 id，例如 `121` 为选股、`4891` 为财富。付费文章只返回源站公开提供的预览内容。

## Parameters
- `id`: 栏目 id，默认为快讯


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
  - `www.barrons.com.cn/`
  - `www.barrons.com.cn/news`
- `target`: `/`
### Rule 2
- `source`:
  - `www.barrons.com.cn/column/:id`
- `target`: `/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "栏目 id 留空则返回快报，可在新站栏目地址 `https://www.barrons.com.cn/column/121` 中找到栏目 id，例如 `121` 为选股、`4891` 为财富。付费文章只返回源站公开提供的预览内容。",
  "example": "/barronschina",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 33,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "栏目",
  "parameters": {
    "id": "栏目 id，默认为快讯"
  },
  "path": "/:id?",
  "radar": [
    {
      "source": [
        "www.barrons.com.cn/",
        "www.barrons.com.cn/news"
      ],
      "target": "/"
    },
    {
      "source": [
        "www.barrons.com.cn/column/:id"
      ],
      "target": "/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "巴伦中文网 - 快报 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59951258674929664",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.barrons.com.cn/news",
      "title": "巴伦中文网 - 快报",
      "type": "feed",
      "url": "rsshub://barronschina"
    }
  ],
  "url": "www.barrons.com.cn"
}
```
