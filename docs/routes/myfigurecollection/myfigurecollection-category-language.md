# MyFigureCollection - 圖片

## Coverage
`index-only`

## Route
- Namespace: `myfigurecollection`
- Namespace Name: `MyFigureCollection`
- Route Path: `/myfigurecollection/:category?/:language?`
- Route Name: `圖片`
- Example: `/myfigurecollection/potd`
- URL: `zh.myfigurecollection.net/browse`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
| 每日圖片 | 每週圖片 | 每月圖片 |
| -------- | -------- | -------- |
| potd     | potw     | potm     |

## Parameters
- `category`: 分类，默认为每日圖片
- `language`: 语言，见上表，默认为空，即 `en`


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
  - `zh.myfigurecollection.net/browse`
  - `zh.myfigurecollection.net/`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "| 每日圖片 | 每週圖片 | 每月圖片 |\n| -------- | -------- | -------- |\n| potd     | potw     | potm     |",
  "example": "/myfigurecollection/potd",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "圖片",
  "parameters": {
    "category": "分类，默认为每日圖片",
    "language": "语言，见上表，默认为空，即 `en`"
  },
  "path": "/:category?/:language?",
  "radar": [
    {
      "source": [
        "zh.myfigurecollection.net/browse",
        "zh.myfigurecollection.net/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "zh.myfigurecollection.net/browse"
}
```
