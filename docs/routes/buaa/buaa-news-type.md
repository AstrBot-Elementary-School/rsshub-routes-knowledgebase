# 北京航空航天大学 - 新闻网

## Coverage
`index-only`

## Route
- Namespace: `buaa`
- Namespace Name: `北京航空航天大学`
- Route Path: `/buaa/news/:type`
- Route Name: `新闻网`
- Example: `/buaa/news/zhxw`
- URL: `news.buaa.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `AlanDecode`
- Source Location: `news/index.ts`
- Source Module: `_None_`

## Description
| 综合新闻 | 信息公告  | 学术文化     | 校园风采  | 科教在线  | 媒体北航  | 专题新闻 | 北航人物 |
| -------- | --------- | ------------ | --------- | --------- | --------- | -------- | -------- |
| zhxw     | xxgg\_new | xsjwhhd\_new | xyfc\_new | kjzx\_new | mtbh\_new | ztxw     | bhrw     |

## Parameters
- `type`: 新闻版块


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
    "university"
  ],
  "description": "| 综合新闻 | 信息公告  | 学术文化     | 校园风采  | 科教在线  | 媒体北航  | 专题新闻 | 北航人物 |\n| -------- | --------- | ------------ | --------- | --------- | --------- | -------- | -------- |\n| zhxw     | xxgg\\_new | xsjwhhd\\_new | xyfc\\_new | kjzx\\_new | mtbh\\_new | ztxw     | bhrw     |",
  "example": "/buaa/news/zhxw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news/index.ts",
  "maintainers": [
    "AlanDecode"
  ],
  "name": "新闻网",
  "parameters": {
    "type": "新闻版块"
  },
  "path": "/news/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
