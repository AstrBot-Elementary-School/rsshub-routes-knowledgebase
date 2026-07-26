# 南开大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `nankai`
- Namespace Name: `南开大学`
- Route Path: `/nankai/graduate/:type?`
- Route Name: `研究生院`
- Example: `/nankai/graduate/zxdt`
- URL: `graduate.nankai.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ladeng07`
- Source Location: `graduate-notice.ts`
- Source Module: `_None_`

## Description
| 最新动态 | 综合信息 | 招生工作 | 培养管理 | 国际交流 | 学科建设 | 学位管理 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| zxdt     | 82       | 83       | 84       | 85       | 86       | 87       |

## Parameters
- `type`: 栏目编号（若为空则默认为"zxdt"）


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
  - `graduate.nankai.edu.cn`
  - `graduate.nankai.edu.cn/:type/list.htm`
- `target`: `/graduate/:type?`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 最新动态 | 综合信息 | 招生工作 | 培养管理 | 国际交流 | 学科建设 | 学位管理 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| zxdt     | 82       | 83       | 84       | 85       | 86       | 87       |",
  "example": "/nankai/graduate/zxdt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "graduate-notice.ts",
  "maintainers": [
    "ladeng07"
  ],
  "name": "研究生院",
  "parameters": {
    "type": "栏目编号（若为空则默认为\"zxdt\"）"
  },
  "path": "/graduate/:type?",
  "radar": [
    {
      "source": [
        "graduate.nankai.edu.cn",
        "graduate.nankai.edu.cn/:type/list.htm"
      ],
      "target": "/graduate/:type?"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "南开大学研究生院-综合信息 - Powered by RSSHub",
      "errorAt": "2026-07-07T20:57:29.624Z",
      "errorMessage": "[GET] \"https://graduate.nankai.edu.cn/82/list.htm\": <no response> fetch failed\n",
      "id": "190697912128162816",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://graduate.nankai.edu.cn/82/list.htm",
      "title": "南开大学研究生院-综合信息",
      "type": "feed",
      "url": "rsshub://nankai/graduate/82"
    }
  ],
  "url": "graduate.nankai.edu.cn"
}
```
