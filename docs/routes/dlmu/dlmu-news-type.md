# 大连海事大学 - 新闻网

## Coverage
`index-only`

## Route
- Namespace: `dlmu`
- Namespace Name: `大连海事大学`
- Route Path: `/dlmu/news/:type`
- Route Name: `新闻网`
- Example: `/dlmu/news/hdyw`
- URL: `news.dlmu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `arjenzhou`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 海大要闻 | 媒体海大 | 综合新闻 | 院系风采 | 海大校报 | 理论园地 | 海大讲坛 | 艺文荟萃 |
| :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|   hdyw   |   mthd   |   zhxw   |   yxfc   |   hdxb   |   llyd   |   hdjt   |   ywhc   |

## Parameters
- `type`: 默认为 `hdyw`


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 海大要闻 | 媒体海大 | 综合新闻 | 院系风采 | 海大校报 | 理论园地 | 海大讲坛 | 艺文荟萃 |\n| :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: |\n|   hdyw   |   mthd   |   zhxw   |   yxfc   |   hdxb   |   llyd   |   hdjt   |   ywhc   |",
  "example": "/dlmu/news/hdyw",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "arjenzhou"
  ],
  "name": "新闻网",
  "parameters": {
    "type": "默认为 `hdyw`"
  },
  "path": "/news/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
