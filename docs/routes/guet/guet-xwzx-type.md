# 桂林电子科技大学 - 新闻资讯

## Coverage
`index-only`

## Route
- Namespace: `guet`
- Namespace Name: `桂林电子科技大学`
- Route Path: `/guet/xwzx/:type?`
- Route Name: `新闻资讯`
- Example: `/guet/xwzx/xykx`
- URL: `www.guet.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `cssxsh`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 桂电要闻 | 校园快讯 | 媒体桂电 | 通知公告 | 校内通知 | 学术信息 |
| -------- | -------- | -------- | -------- | -------- | -------- |
| gdyw     | xykx     | mtgd     | tzgg     | xntz     | xsxx     |

## Parameters
- `type`: 资讯类型，如下表


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 桂电要闻 | 校园快讯 | 媒体桂电 | 通知公告 | 校内通知 | 学术信息 |\n| -------- | -------- | -------- | -------- | -------- | -------- |\n| gdyw     | xykx     | mtgd     | tzgg     | xntz     | xsxx     |",
  "example": "/guet/xwzx/xykx",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "cssxsh"
  ],
  "name": "新闻资讯",
  "parameters": {
    "type": "资讯类型，如下表"
  },
  "path": "/xwzx/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
