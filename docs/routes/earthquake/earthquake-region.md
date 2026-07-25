# 地震速报 - 中国地震局

## Coverage
`index-only`

## Route
- Namespace: `earthquake`
- Namespace Name: `地震速报`
- Route Path: `/earthquake/:region?`
- Route Name: `中国地震局`
- Example: `/earthquake`
- URL: `www.cea.gov.cn/cea/xwzx/zqsd/index.html`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `LogicJake`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
可通过全局过滤参数订阅您感兴趣的地区.

## Parameters
- `region`: 区域，0全部，1国内（默认），2国外


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
  - `www.cea.gov.cn/cea/xwzx/zqsd/index.html`
  - `www.cea.gov.cn/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "description": "可通过全局过滤参数订阅您感兴趣的地区.",
  "example": "/earthquake",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 121,
  "location": "index.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "中国地震局",
  "parameters": {
    "region": "区域，0全部，1国内（默认），2国外"
  },
  "path": "/:region?",
  "radar": [
    {
      "source": [
        "www.cea.gov.cn/cea/xwzx/zqsd/index.html",
        "www.cea.gov.cn/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "中国地震局震情速递 - Powered by RSSHub",
      "errorAt": "2025-11-12T02:03:39.013Z",
      "errorMessage": "[POST] \"https://www.cea.gov.cn/eportal/ui?struts.portlet.mode=view&struts.portlet.action=/portlet/expressEarthquake!queryExpressEarthquakeList.action&pageId=363409&moduleId=a852ba487b534470a84a30f00e7d6670\": 403 Forbidden\n[POST] \"https://www.cea.gov.cn/eportal/ui?struts.portlet.mode=view&struts.portlet.action=/portlet/expressEarthquake!queryExpressEarthquakeList.action&pageId=363409&moduleId=a852ba487b534470a84a30f00e7d6670\": 403 Forbidden\n",
      "id": "58939140174548992",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cea.gov.cn/cea/xwzx/zqsd/index.html",
      "title": "中国地震局震情速递",
      "type": "feed",
      "url": "rsshub://earthquake"
    },
    {
      "description": "中国地震局震情速递 - Powered by RSSHub",
      "errorAt": "2026-07-20T12:38:50.188Z",
      "errorMessage": "[POST] \"https://www.cea.gov.cn/eportal/ui?struts.portlet.mode=view&struts.portlet.action=/portlet/expressEarthquake!queryExpressEarthquakeList.action&pageId=363409&moduleId=a852ba487b534470a84a30f00e7d6670\": 403 Forbidden\n",
      "id": "60836830967846986",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cea.gov.cn/cea/xwzx/zqsd/index.html",
      "title": "中国地震局震情速递",
      "type": "feed",
      "url": "rsshub://earthquake/0"
    }
  ],
  "url": "www.cea.gov.cn/cea/xwzx/zqsd/index.html"
}
```
