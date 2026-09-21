# 淘宝网 - 数据库内核月报

## Coverage
`index-only`

## Route
- Namespace: `taobao`
- Namespace Name: `淘宝网`
- Route Path: `/taobao/mysql/monthly`
- Route Name: `数据库内核月报`
- Example: `/taobao/mysql/monthly`
- URL: `mysql.taobao.org`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `mysql.ts`
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
  - `mysql.taobao.org/monthly/`
- `target`: `/mysql/monthly`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/taobao/mysql/monthly",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 20,
  "location": "mysql.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "数据库内核月报",
  "path": "/mysql/monthly",
  "radar": [
    {
      "source": [
        "mysql.taobao.org/monthly/"
      ],
      "target": "/mysql/monthly"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 321761120753 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "数据库内核月报, 来着阿里云 PolarDB 数据库内核团队。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "167615877995447296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://mysql.taobao.org/monthly/",
      "title": "数据库内核月报",
      "type": "feed",
      "url": "rsshub://taobao/mysql/monthly"
    }
  ],
  "url": "mysql.taobao.org",
  "view": 0
}
```
