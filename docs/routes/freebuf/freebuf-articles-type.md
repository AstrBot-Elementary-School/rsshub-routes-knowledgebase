# FreeBuf - 文章

## Coverage
`index-only`

## Route
- Namespace: `freebuf`
- Namespace Name: `FreeBuf`
- Route Path: `/freebuf/articles/:type`
- Route Name: `文章`
- Example: `/freebuf/articles/web`
- URL: `freebuf.com`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `trganda`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
Freebuf 的文章页面带有反爬虫机制，所以目前无法获取文章的完整内容。
:::

## Parameters
- `type`: 文章类别


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
  - `freebuf.com/articles/:type/*.html`
  - `freebuf.com/articles/:type`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "::: tip\nFreebuf 的文章页面带有反爬虫机制，所以目前无法获取文章的完整内容。\n:::",
  "example": "/freebuf/articles/web",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 78,
  "location": "index.ts",
  "maintainers": [
    "trganda"
  ],
  "name": "文章",
  "parameters": {
    "type": "文章类别"
  },
  "path": "/articles/:type",
  "radar": [
    {
      "source": [
        "freebuf.com/articles/:type/*.html",
        "freebuf.com/articles/:type"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Freebuf web - Powered by RSSHub",
      "errorAt": "2026-07-25T17:23:12.305Z",
      "errorMessage": "Authentication failed. Access denied.\n/freebuf/articles/web\n[GET] \"https://www.freebuf.com/fapi/frontend/category/list?name=web&page=1&limit=20&select=0&order=0&type=category\": 405 Not Allowed\n[GET] \"https://www.freebuf.com/fapi/frontend/category/list?name=web&page=1&limit=20&select=0&order=0&type=category\": 405 Not Allowed\n",
      "id": "52357479513292810",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.freebuf.com/articles/web",
      "title": "Freebuf web",
      "type": "feed",
      "url": "rsshub://freebuf/articles/web"
    },
    {
      "description": "Freebuf system - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "83007201386261504",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.freebuf.com/articles/system",
      "title": "Freebuf system",
      "type": "feed",
      "url": "rsshub://freebuf/articles/system"
    }
  ]
}
```
