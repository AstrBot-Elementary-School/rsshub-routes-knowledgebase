# 南开大学 - 研究生招生网

## Coverage
`index-only`

## Route
- Namespace: `nankai`
- Namespace Name: `南开大学`
- Route Path: `/nankai/yzb/:type?`
- Route Name: `研究生招生网`
- Example: `/nankai/yzb/5509`
- URL: `yzb.nankai.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `sddzhyc`
- Source Location: `yzb.ts`
- Source Module: `_None_`

## Description
| 硕士招生 | 博士招生 | 港澳台研究生最新信息 |
| -------- | -------- | -------------------- |
| 5509     | 2552     | 2562                 |

## Parameters
- `type`: 栏目名（若为空则默认为“硕士招生”）


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
  - `yzb.nankai.edu.cn`
  - `yzb.nankai.edu.cn/:type/list.htm`
- `target`: `/yzb/:type?`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 硕士招生 | 博士招生 | 港澳台研究生最新信息 |\n| -------- | -------- | -------------------- |\n| 5509     | 2552     | 2562                 |",
  "example": "/nankai/yzb/5509",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "yzb.ts",
  "maintainers": [
    "sddzhyc"
  ],
  "name": "研究生招生网",
  "parameters": {
    "type": "栏目名（若为空则默认为“硕士招生”）"
  },
  "path": "/yzb/:type?",
  "radar": [
    {
      "source": [
        "yzb.nankai.edu.cn",
        "yzb.nankai.edu.cn/:type/list.htm"
      ],
      "target": "/yzb/:type?"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "南开大学研究生招生网-硕士招生 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "167782987907531776",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://yzb.nankai.edu.cn/5509/list.htm",
      "title": "南开大学研究生招生网-硕士招生",
      "type": "feed",
      "url": "rsshub://nankai/yzb/5509"
    }
  ],
  "url": "yzb.nankai.edu.cn"
}
```
