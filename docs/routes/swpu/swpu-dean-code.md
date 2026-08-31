# 西南石油大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `swpu`
- Namespace Name: `西南石油大学`
- Route Path: `/swpu/dean/:code`
- Route Name: `教务处`
- Example: `/swpu/dean/tzgg`
- URL: `swpu.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `CYTMWIA`
- Source Location: `dean.ts`
- Source Module: `_None_`

## Description
| 栏目 | 通知公告 | 新闻报道 | 视点声音 |
| ---- | -------- | -------- | -------- |
| 代码 | tzgg     | xwbd     | sdsy     |

## Parameters
- `code`: 栏目代码


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
  - `swpu.edu.cn/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 栏目 | 通知公告 | 新闻报道 | 视点声音 |\n| ---- | -------- | -------- | -------- |\n| 代码 | tzgg     | xwbd     | sdsy     |",
  "example": "/swpu/dean/tzgg",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "dean.ts",
  "maintainers": [
    "CYTMWIA"
  ],
  "name": "教务处",
  "parameters": {
    "code": "栏目代码"
  },
  "path": "/dean/:code",
  "radar": [
    {
      "source": [
        "swpu.edu.cn/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "西南石油大学教务处 通知公告 - Powered by RSSHub",
      "errorAt": "2025-12-31T07:03:20.303Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "105536397884337152",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.swpu.edu.cn/dean/tzgg.htm",
      "title": "西南石油大学教务处 通知公告",
      "type": "feed",
      "url": "rsshub://swpu/dean/tzgg"
    }
  ],
  "url": "swpu.edu.cn/"
}
```
