# 中国科学院 - 成果转化

## Coverage
`index-only`

## Route
- Namespace: `cas`
- Namespace Name: `中国科学院`
- Route Path: `/cas/cg/:caty?`
- Route Name: `成果转化`
- Example: `/cas/cg/cgzhld`
- URL: `www.cas.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `cg/index.ts`
- Source Module: `_None_`

## Description
| 工作动态 | 科技成果转移转化亮点工作 |
| -------- | ------------------------ |
| zh       | cgzhld                   |

## Parameters
- `caty`: 分类，见下表，默认为工作动态


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
  - `www.cas.cn/cg/:caty?`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 工作动态 | 科技成果转移转化亮点工作 |\n| -------- | ------------------------ |\n| zh       | cgzhld                   |",
  "example": "/cas/cg/cgzhld",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "cg/index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "成果转化",
  "parameters": {
    "caty": "分类，见下表，默认为工作动态"
  },
  "path": "/cg/:caty?",
  "radar": [
    {
      "source": [
        "www.cas.cn/cg/:caty?"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
