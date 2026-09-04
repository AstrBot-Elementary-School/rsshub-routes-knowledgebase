# 中指研究院 - 报告

## Coverage
`index-only`

## Route
- Namespace: `cih-index`
- Namespace Name: `中指研究院`
- Route Path: `/cih-index/report/list/:report?`
- Route Name: `报告`
- Example: `/cih-index/report/list/p1-oaddtime-ddesc`
- URL: `www.cih-index.com/report/list/p1-oaddtime-ddesc`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `report.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `report`: 报告 id，可在 URL 中找到，留空为 `p1-oaddtime-ddesc`


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
  - `www.cih-index.com/report/list/:report`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/cih-index/report/list/p1-oaddtime-ddesc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 92,
  "location": "report.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "报告",
  "parameters": {
    "report": "报告 id，可在 URL 中找到，留空为 `p1-oaddtime-ddesc`"
  },
  "path": "/report/list/:report?",
  "radar": [
    {
      "source": [
        "www.cih-index.com/report/list/:report"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "中指云基于中指研究院多年研究积累，提供最全房地产行业报告，可免费阅读房地产政策解读、市场趋势、房企研究及物业行业分析报告，可下载PDF格式报告，深度洞察房地产行业动向。 - Powered by RSSHub",
      "errorAt": "2026-07-27T12:43:35.566Z",
      "errorMessage": "[GET] \"https://www.cih-index.com/report/list/f2022041315362473358-p1-oaddtime-ddesc\": 429 Too Many Requests\n",
      "id": "150104102533230592",
      "image": "https://www.cih-index.com/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.cih-index.com/report/list/f2022041315362473358-p1-oaddtime-ddesc",
      "title": "政策解读 - 中指报告",
      "type": "feed",
      "url": "rsshub://cih-index/report/list/f2022041315362473358-p1-oaddtime-ddesc"
    },
    {
      "description": "中指云基于中指研究院多年研究积累，提供最全房地产行业报告，可免费阅读房地产政策解读、市场趋势、房企研究及物业行业分析报告，可下载PDF格式报告，深度洞察房地产行业动向。 - Powered by RSSHub",
      "errorAt": "2026-07-27T21:02:23.759Z",
      "errorMessage": "[GET] \"https://www.cih-index.com/report/list/p1-oaddtime-ddesc\": 429 Too Many Requests\n",
      "id": "149713189464210432",
      "image": "https://www.cih-index.com/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.cih-index.com/report/list/p1-oaddtime-ddesc",
      "title": "中指报告",
      "type": "feed",
      "url": "rsshub://cih-index/report/list"
    }
  ],
  "url": "www.cih-index.com/report/list/p1-oaddtime-ddesc"
}
```
