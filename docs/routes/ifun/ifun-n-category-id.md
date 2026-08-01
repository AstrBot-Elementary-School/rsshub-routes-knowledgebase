# 趣集 - 盐选故事分类

## Coverage
`index-only`

## Route
- Namespace: `ifun`
- Namespace Name: `趣集`
- Route Path: `/ifun/n/category/:id?`
- Route Name: `盐选故事分类`
- Example: `/ifun/n/category`
- URL: `n.ifun.cool`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `n/category.ts`
- Source Module: `_None_`

## Description
| 名称     | ID |
| -------- | -- |
| 全部     |    |
| 通告     | 1  |
| 故事盐选 | 2  |
| 趣集精选 | 3  |

## Parameters
- `id`: 分类 id，默认为空，即全部，见下表


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
  - `n.ifun.cool`
- `target`: `/n/category/:id?`
### Rule 2
- `title`: `全部`
- `source`:
  - `n.ifun.cool`
- `target`: `/n/category`
### Rule 3
- `title`: `通告`
- `source`:
  - `n.ifun.cool`
- `target`: `/n/category/1`
### Rule 4
- `title`: `盐选故事`
- `source`:
  - `n.ifun.cool`
- `target`: `/n/category/2`
### Rule 5
- `title`: `趣集精选`
- `source`:
  - `n.ifun.cool`
- `target`: `/n/category/3`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 名称     | ID |\n| -------- | -- |\n| 全部     |    |\n| 通告     | 1  |\n| 故事盐选 | 2  |\n| 趣集精选 | 3  |",
  "example": "/ifun/n/category",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 10,
  "location": "n/category.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "盐选故事分类",
  "parameters": {
    "id": "分类 id，默认为空，即全部，见下表"
  },
  "path": "/n/category/:id?",
  "radar": [
    {
      "source": [
        "n.ifun.cool"
      ],
      "target": "/n/category/:id?"
    },
    {
      "source": [
        "n.ifun.cool"
      ],
      "target": "/n/category",
      "title": "全部"
    },
    {
      "source": [
        "n.ifun.cool"
      ],
      "target": "/n/category/1",
      "title": "通告"
    },
    {
      "source": [
        "n.ifun.cool"
      ],
      "target": "/n/category/2",
      "title": "盐选故事"
    },
    {
      "source": [
        "n.ifun.cool"
      ],
      "target": "/n/category/3",
      "title": "趣集精选"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "趣集 - Powered by RSSHub",
      "errorAt": "2025-01-19T17:37:36.683Z",
      "errorMessage": "Cannot read properties of undefined (reading 'find')\nCannot read properties of undefined (reading 'find')\n",
      "id": "86604116820537344",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://n.ifun.cool/",
      "title": "趣集",
      "type": "feed",
      "url": "rsshub://ifun/n/category"
    }
  ],
  "url": "n.ifun.cool",
  "view": 0
}
```
