# 哈尔滨工程大学 - 水声工程学院

## Coverage
`index-only`

## Route
- Namespace: `hrbeu`
- Namespace Name: `哈尔滨工程大学`
- Route Path: `/hrbeu/uae/:id`
- Route Name: `水声工程学院`
- Example: `/hrbeu/uae/xwdt`
- URL: `yjsy.hrbeu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Derekmini`
- Source Location: `uae/news.ts`
- Source Module: `_None_`

## Description
| 新闻动态 | 通知公告 | 科学研究 / 科研动态 |
| :------: | :------: | :-----------------: |
|   xwdt   |   tzgg   |      kxyj-kydt      |

## Parameters
- `id`: 栏目编号，在 `URL` 中获取，如果有多级编号，将 `/` 替换为 `-`。


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
  - `uae.hrbeu.edu.cn/:id.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 新闻动态 | 通知公告 | 科学研究 / 科研动态 |\n| :------: | :------: | :-----------------: |\n|   xwdt   |   tzgg   |      kxyj-kydt      |",
  "example": "/hrbeu/uae/xwdt",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "uae/news.ts",
  "maintainers": [
    "Derekmini"
  ],
  "name": "水声工程学院",
  "parameters": {
    "id": "栏目编号，在 `URL` 中获取，如果有多级编号，将 `/` 替换为 `-`。"
  },
  "path": "/uae/:id",
  "radar": [
    {
      "source": [
        "uae.hrbeu.edu.cn/:id.htm"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
