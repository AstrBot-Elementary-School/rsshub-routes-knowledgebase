# 北极星电力网 - 光伏

## Coverage
`index-only`

## Route
- Namespace: `bjx`
- Namespace Name: `北极星电力网`
- Route Path: `/bjx/gf/:type`
- Route Name: `光伏`
- Example: `/bjx/gf/sc`
- URL: `www.bjx.com.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `Sxuet`
- Source Location: `types.ts`
- Source Module: `_None_`

## Description
`:type` 类型可选如下

| 要闻 | 政策 | 市场行情 | 企业动态 | 独家观点 | 项目工程 | 招标采购 | 财经 | 国际行情 | 价格趋势 | 技术跟踪 |
| ---- | ---- | -------- | -------- | -------- | -------- | -------- | ---- | -------- | -------- | -------- |
| yw   | zc   | sc       | mq       | dj       | xm       | zb       | cj   | gj       | sj       | js       |

## Parameters
- `type`: 分类，北极星光伏最后的`type`字段


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "`:type` 类型可选如下\n\n| 要闻 | 政策 | 市场行情 | 企业动态 | 独家观点 | 项目工程 | 招标采购 | 财经 | 国际行情 | 价格趋势 | 技术跟踪 |\n| ---- | ---- | -------- | -------- | -------- | -------- | -------- | ---- | -------- | -------- | -------- |\n| yw   | zc   | sc       | mq       | dj       | xm       | zb       | cj   | gj       | sj       | js       |",
  "example": "/bjx/gf/sc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 12,
  "location": "types.ts",
  "maintainers": [
    "Sxuet"
  ],
  "name": "光伏",
  "parameters": {
    "type": "分类，北极星光伏最后的`type`字段"
  },
  "path": "/gf/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "北极星太阳能光大网要闻 - Powered by RSSHub",
      "errorAt": "2026-03-24T09:51:13.872Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "62791268472274944",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://guangfu.bjx.com.cn/yw/",
      "title": "北极星太阳能光大网要闻",
      "type": "feed",
      "url": "rsshub://bjx/gf/yw"
    },
    {
      "description": "北极星太阳能光大网市场 - Powered by RSSHub",
      "errorAt": "2026-03-24T07:22:37.547Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "62791006416355328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://guangfu.bjx.com.cn/sc/",
      "title": "北极星太阳能光大网市场",
      "type": "feed",
      "url": "rsshub://bjx/gf/sc"
    }
  ]
}
```
