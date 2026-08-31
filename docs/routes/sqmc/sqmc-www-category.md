# 新乡医学院三全学院 - 官网信息

## Coverage
`index-only`

## Route
- Namespace: `sqmc`
- Namespace Name: `新乡医学院三全学院`
- Route Path: `/sqmc/www/:category?`
- Route Name: `官网信息`
- Example: `/sqmc/www/3157`
- URL: `sqmc.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nyaShine`
- Source Location: `www.ts`
- Source Module: `_None_`

## Description
| 学校要闻 | 通知 | 学术讲座 | 基层风采书院 | 基层风采院系 | 外媒报道 | 三全学院报 |
| -------- | ---- | -------- | ------------ | ------------ | -------- | ---------- |
| 3157     | 3187 | 3188     | 3185         | 3186         | 3199     | 3200       |

## Parameters
- `category`: 分类ID，默认为`3157`


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
  - `sqmc.edu.cn/:category/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学校要闻 | 通知 | 学术讲座 | 基层风采书院 | 基层风采院系 | 外媒报道 | 三全学院报 |\n| -------- | ---- | -------- | ------------ | ------------ | -------- | ---------- |\n| 3157     | 3187 | 3188     | 3185         | 3186         | 3199     | 3200       |",
  "example": "/sqmc/www/3157",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "www.ts",
  "maintainers": [
    "nyaShine"
  ],
  "name": "官网信息",
  "parameters": {
    "category": "分类ID，默认为`3157`"
  },
  "path": "/www/:category?",
  "radar": [
    {
      "source": [
        "sqmc.edu.cn/:category/list.htm"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
