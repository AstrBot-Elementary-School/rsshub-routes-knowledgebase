# 腾讯 - 新型冠状病毒肺炎疫情实时追踪 - 省市疫情数据

## Coverage
`index-only`

## Route
- Namespace: `tencent`
- Namespace Name: `腾讯`
- Route Path: `/tencent/news/coronavirus/data/:province?/:city?`
- Route Name: `新型冠状病毒肺炎疫情实时追踪 - 省市疫情数据`
- Example: `/tencent/news/coronavirus/data/湖北/武汉`
- URL: `tencent.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `CaoMeiYouRen`
- Source Location: `news/coronavirus/data.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `province`: 省/直辖市名，缺省则返回国内数据
- `city`: 城市名，缺省则返回全省数据。直辖市请使用区/县名。


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/tencent/news/coronavirus/data/湖北/武汉",
  "heat": 0,
  "location": "news/coronavirus/data.tsx",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "name": "新型冠状病毒肺炎疫情实时追踪 - 省市疫情数据",
  "parameters": {
    "city": "城市名，缺省则返回全省数据。直辖市请使用区/县名。",
    "province": "省/直辖市名，缺省则返回国内数据"
  },
  "path": "/news/coronavirus/data/:province?/:city?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
