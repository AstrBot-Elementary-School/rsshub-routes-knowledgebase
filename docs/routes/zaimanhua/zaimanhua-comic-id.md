# 再漫画 - 漫画更新

## Coverage
`index-only`

## Route
- Namespace: `zaimanhua`
- Namespace Name: `再漫画`
- Route Path: `/zaimanhua/comic/:id`
- Route Name: `漫画更新`
- Example: `/zaimanhua/comic/57069`
- URL: `manhua.zaimanhua.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `kjasn`
- Source Location: `comic.ts`
- Source Module: `_None_`

## Description
::: Warning
未登录用户无法获取到所有漫画，需要设置`ZAIMANHUA_TOKEN`环境变量以使用 API 授权访问。
且由于源网站本身的限制，建议尽量在部署于中国大陆网络内的 RSSHub 节点中使用本路由。若在海外网络环境中使用，即使设置了`ZAIMANHUA_TOKEN`环境变量，也可能无法获取全部漫画。
:::

## Parameters
- `id`: 漫画ID


## Features
- `requireConfig`: [{"description": "用户登录后，可以从浏览器开发者工具 Network 面板中的请求信息中获取 token，使用请求中的 `Authorization` 的值，完整设置为 `Bearer <token>`，或直接设置 token 并由路由自动补齐 `Bearer ` 前缀。", "name": "ZAIMANHUA_TOKEN", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `manhua.zaimanhua.com/details`
  - `manhua.zaimanhua.com/details/:id`
- `target`: `/comic/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "::: Warning\n未登录用户无法获取到所有漫画，需要设置`ZAIMANHUA_TOKEN`环境变量以使用 API 授权访问。\n且由于源网站本身的限制，建议尽量在部署于中国大陆网络内的 RSSHub 节点中使用本路由。若在海外网络环境中使用，即使设置了`ZAIMANHUA_TOKEN`环境变量，也可能无法获取全部漫画。\n:::",
  "example": "/zaimanhua/comic/57069",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "用户登录后，可以从浏览器开发者工具 Network 面板中的请求信息中获取 token，使用请求中的 `Authorization` 的值，完整设置为 `Bearer <token>`，或直接设置 token 并由路由自动补齐 `Bearer ` 前缀。",
        "name": "ZAIMANHUA_TOKEN",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "comic.ts",
  "maintainers": [
    "kjasn"
  ],
  "name": "漫画更新",
  "parameters": {
    "id": "漫画ID"
  },
  "path": "/comic/:id",
  "radar": [
    {
      "source": [
        "manhua.zaimanhua.com/details",
        "manhua.zaimanhua.com/details/:id"
      ],
      "target": "/comic/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "再漫画 - 艾尔登法环剧情解析漫画 - Powered by RSSHub",
      "errorAt": "2026-01-20T08:30:58.306Z",
      "errorMessage": "[GET] \"https://manhua.zaimanhua.com/api/v1/comic2/comic/detail?id=73129\": <no response> fetch failed\n",
      "id": "166081220820177920",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://manhua.zaimanhua.com/details/73129",
      "title": "再漫画 - 艾尔登法环剧情解析漫画",
      "type": "feed",
      "url": "rsshub://zaimanhua/comic/73129"
    },
    {
      "description": "再漫画 - 一击男ONE原作版 - Powered by RSSHub",
      "errorAt": "2025-07-31T02:30:45.447Z",
      "errorMessage": "Cannot read properties of undefined (reading 'title')\n",
      "id": "144946872242255872",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://manhua.zaimanhua.com/details/48194",
      "title": "再漫画 - 一击男ONE原作版",
      "type": "feed",
      "url": "rsshub://zaimanhua/comic/48194"
    }
  ]
}
```
