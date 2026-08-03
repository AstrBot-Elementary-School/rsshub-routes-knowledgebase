# 北京林业大学 - 绿色新闻网

## Coverage
`index-only`

## Route
- Namespace: `bjfu`
- Namespace Name: `北京林业大学`
- Route Path: `/bjfu/news/:type`
- Route Name: `绿色新闻网`
- Example: `/bjfu/news/lsyw`
- URL: `graduate.bjfu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `markmingjie`
- Source Location: `news/index.ts`
- Source Module: `_None_`

## Description
| 绿色要闻 | 校园动态 | 教学科研 | 党建思政 | 一周排行 |
| -------- | -------- | -------- | -------- | -------- |
| lsyw     | xydt     | jxky     | djsz     | yzph     |

## Parameters
- `type`: 新闻栏目


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
  - `news.bjfu.edu.cn/:type/index.html`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 绿色要闻 | 校园动态 | 教学科研 | 党建思政 | 一周排行 |\n| -------- | -------- | -------- | -------- | -------- |\n| lsyw     | xydt     | jxky     | djsz     | yzph     |",
  "example": "/bjfu/news/lsyw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news/index.ts",
  "maintainers": [
    "markmingjie"
  ],
  "name": "绿色新闻网",
  "parameters": {
    "type": "新闻栏目"
  },
  "path": "/news/:type",
  "radar": [
    {
      "source": [
        "news.bjfu.edu.cn/:type/index.html"
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
