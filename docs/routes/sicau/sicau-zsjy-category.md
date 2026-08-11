# 四川农业大学 - 招生就业

## Coverage
`index-only`

## Route
- Namespace: `sicau`
- Namespace Name: `四川农业大学`
- Route Path: `/sicau/zsjy/:category?`
- Route Name: `招生就业`
- Example: `/sicau/zsjy/bkszs`
- URL: `dky.sicau.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `zsjy.ts`
- Source Module: `_None_`

## Description
| 本科生招生 | 研究生招生 | 毕业生选录指南 |
| ---------- | ---------- | -------------- |
| bkszs      | yjszs      | bysxlzn        |

## Parameters
- `category`: 分类，见下表，默认为本科生招生


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
  - `dky.sicau.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 本科生招生 | 研究生招生 | 毕业生选录指南 |\n| ---------- | ---------- | -------------- |\n| bkszs      | yjszs      | bysxlzn        |",
  "example": "/sicau/zsjy/bkszs",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "zsjy.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "招生就业",
  "parameters": {
    "category": "分类，见下表，默认为本科生招生"
  },
  "path": "/zsjy/:category?",
  "radar": [
    {
      "source": [
        "dky.sicau.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "dky.sicau.edu.cn/"
}
```
