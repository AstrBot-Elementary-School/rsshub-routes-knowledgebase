# 中国教育考试网 - 日本语能力测试 JLPT 通知

## Coverage
`index-only`

## Route
- Namespace: `neea`
- Namespace Name: `中国教育考试网`
- Route Path: `/neea/jlpt`
- Route Name: `日本语能力测试 JLPT 通知`
- Example: `/neea/jlpt`
- URL: `jlpt.neea.cn`
- Language: `_None_`
- Categories: `study`
- Maintainers: `nczitzk`
- Source Location: `jlpt.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `jlpt.neea.cn`
- `target`: `/jlpt`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/neea/jlpt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 14,
  "location": "jlpt.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "日本语能力测试 JLPT 通知",
  "path": "/jlpt",
  "radar": [
    {
      "source": [
        "jlpt.neea.cn"
      ],
      "target": "/jlpt"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "维护通知 - 中国教育考试网 - Powered by RSSHub",
      "errorAt": "2026-06-10T11:52:17.733Z",
      "errorMessage": "[GET] \"https://jlpt.neea.cn/index.do\": 412 Precondition Failed\n530 \n[GET] \"https://jlpt.neea.cn/index.do\": <no response> fetch failed (Connect Timeout Error (attempted address: jlpt.neea.cn:443, timeout: 10000ms))\n",
      "id": "106226114484296704",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jlpt.neea.cn/index.do",
      "title": "中国教育考试网 -",
      "type": "feed",
      "url": "rsshub://neea/jlpt"
    }
  ],
  "url": "jlpt.neea.cn",
  "view": 0
}
```
