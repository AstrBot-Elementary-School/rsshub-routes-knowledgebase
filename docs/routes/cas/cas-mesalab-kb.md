# 中国科学院 - 信息工程研究所 第二研究室 处理架构组 知识库

## Coverage
`index-only`

## Route
- Namespace: `cas`
- Namespace Name: `中国科学院`
- Route Path: `/cas/mesalab/kb`
- Route Name: `信息工程研究所 第二研究室 处理架构组 知识库`
- Example: `/cas/mesalab/kb`
- URL: `www.mesalab.cn/f/article/articleList`
- Language: `_None_`
- Categories: `university`
- Maintainers: `renzhexigua`
- Source Location: `mesalab/kb.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `www.mesalab.cn/f/article/articleList`
  - `www.mesalab.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/cas/mesalab/kb",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "mesalab/kb.ts",
  "maintainers": [
    "renzhexigua"
  ],
  "name": "信息工程研究所 第二研究室 处理架构组 知识库",
  "parameters": {},
  "path": "/mesalab/kb",
  "radar": [
    {
      "source": [
        "www.mesalab.cn/f/article/articleList",
        "www.mesalab.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.mesalab.cn/f/article/articleList"
}
```
