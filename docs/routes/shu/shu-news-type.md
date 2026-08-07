# 上海大学 - 官网通知公告

## Coverage
`index-only`

## Route
- Namespace: `shu`
- Namespace Name: `上海大学`
- Route Path: `/shu/news/:type?`
- Route Name: `官网通知公告`
- Example: `/shu/news/tzgg`
- URL: `www.shu.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `lonelyion, GhhG123`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 重要新闻 |
| -------- | -------- |
| tzgg     | zyxw     |

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
  - `www.shu.edu.cn/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 重要新闻 |\n| -------- | -------- |\n| tzgg     | zyxw     |",
  "example": "/shu/news/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "index.ts",
  "maintainers": [
    "lonelyion",
    "GhhG123"
  ],
  "name": "官网通知公告",
  "parameters": {
    "type": "分类，默认为通知公告"
  },
  "path": "/news/:type?",
  "radar": [
    {
      "source": [
        "www.shu.edu.cn/"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "上海大学 - 通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67454017244017664",
      "image": "https://www.shu.edu.cn/__local/0/08/C6/1EABE492B0CF228A5564D6E6ABE_779D1EE3_5BF7.png",
      "ownerUserId": null,
      "siteUrl": "https://www.shu.edu.cn/tzgg.htm",
      "title": "上海大学 - 通知公告",
      "type": "feed",
      "url": "rsshub://shu/news"
    },
    {
      "description": "上海大学 - 重要新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84816968418040832",
      "image": "https://www.shu.edu.cn/__local/0/08/C6/1EABE492B0CF228A5564D6E6ABE_779D1EE3_5BF7.png",
      "ownerUserId": null,
      "siteUrl": "https://www.shu.edu.cn/zyxw.htm",
      "title": "上海大学 - 重要新闻",
      "type": "feed",
      "url": "rsshub://shu/news/zyxw"
    }
  ],
  "url": "www.shu.edu.cn/"
}
```
