# 上海大学 - 国际部港澳台办公室

## Coverage
`index-only`

## Route
- Namespace: `shu`
- Namespace Name: `上海大学`
- Route Path: `/shu/global/:type?`
- Route Name: `国际部港澳台办公室`
- Example: `/shu/global/tzgg`
- URL: `global.shu.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `GhhG123`
- Source Location: `global.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 新闻速递 |
| -------- | -------- |
| tzgg     | xwsd     |

## Parameters
- `type`: 分类，默认为通知公告


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
  - `global.shu.edu.cn/cd/tzgg.htm`
  - `global.shu.edu.cn/cd/xwsd.htm`
- `target`: `/global`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 新闻速递 |\n| -------- | -------- |\n| tzgg     | xwsd     |",
  "example": "/shu/global/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "global.ts",
  "maintainers": [
    "GhhG123"
  ],
  "name": "国际部港澳台办公室",
  "parameters": {
    "type": "分类，默认为通知公告"
  },
  "path": "/global/:type?",
  "radar": [
    {
      "source": [
        "global.shu.edu.cn/cd/tzgg.htm",
        "global.shu.edu.cn/cd/xwsd.htm"
      ],
      "target": "/global"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "上海大学国际部港澳台-通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84817247436783616",
      "image": "https://www.shu.edu.cn/__local/0/08/C6/1EABE492B0CF228A5564D6E6ABE_779D1EE3_5BF7.png",
      "ownerUserId": null,
      "siteUrl": "https://global.shu.edu.cn/cd/tzgg.htm",
      "title": "上海大学国际部港澳台-通知公告",
      "type": "feed",
      "url": "rsshub://shu/global/tzgg"
    }
  ],
  "url": "global.shu.edu.cn/"
}
```
