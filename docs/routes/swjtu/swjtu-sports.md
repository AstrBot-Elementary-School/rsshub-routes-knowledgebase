# 西南交通大学 - 体育学院

## Coverage
`index-only`

## Route
- Namespace: `swjtu`
- Namespace Name: `西南交通大学`
- Route Path: `/swjtu/sports`
- Route Name: `体育学院`
- Example: `/swjtu/sports`
- URL: `www.swjtu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `AzureG03`
- Source Location: `sports.ts`
- Source Module: `_None_`

## Description
新闻资讯

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `sports.swjtu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "新闻资讯",
  "example": "/swjtu/sports",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "sports.ts",
  "maintainers": [
    "AzureG03"
  ],
  "name": "体育学院",
  "parameters": {},
  "path": "/sports",
  "radar": [
    {
      "source": [
        "sports.swjtu.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
