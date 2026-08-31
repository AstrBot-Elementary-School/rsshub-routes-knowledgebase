# 云听 - 节目

## Coverage
`index-only`

## Route
- Namespace: `radio`
- Namespace Name: `云听`
- Route Path: `/radio/:id`
- Route Name: `节目`
- Example: `/radio/1552135`
- URL: `radio.cn`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `kt286, nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
如果订阅 [共和国追梦人](http://www.radio.cn/pc-portal/sanji/detail.html?columnId=1552135)，其 URL 为 `https://www.radio.cn/pc-portal/sanji/detail.html?columnId=1552135`，可以得到 `columnId` 为 `1552135`

所以对应路由为 [`/radio/1552135`](https://rsshub.app/radio/1552135)

::: tip
该路由仅适用于更新时间较早的电台节目，如 [共和国追梦人](http://www.radio.cn/pc-portal/sanji/detail.html?columnId=1552135)

与适用于 [专辑](#yun-ting-zhuan-ji) 路由的专辑其 `columnId` 长度相比，它们的 `columnId` 长度较短
:::

## Parameters
- `id`: 专辑 id，可在对应专辑页面的 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "如果订阅 [共和国追梦人](http://www.radio.cn/pc-portal/sanji/detail.html?columnId=1552135)，其 URL 为 `https://www.radio.cn/pc-portal/sanji/detail.html?columnId=1552135`，可以得到 `columnId` 为 `1552135`\n\n所以对应路由为 [`/radio/1552135`](https://rsshub.app/radio/1552135)\n\n::: tip\n该路由仅适用于更新时间较早的电台节目，如 [共和国追梦人](http://www.radio.cn/pc-portal/sanji/detail.html?columnId=1552135)\n\n与适用于 [专辑](#yun-ting-zhuan-ji) 路由的专辑其 `columnId` 长度相比，它们的 `columnId` 长度较短\n:::",
  "example": "/radio/1552135",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "kt286",
    "nczitzk"
  ],
  "name": "节目",
  "parameters": {
    "id": "专辑 id，可在对应专辑页面的 URL 中找到"
  },
  "path": "/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
