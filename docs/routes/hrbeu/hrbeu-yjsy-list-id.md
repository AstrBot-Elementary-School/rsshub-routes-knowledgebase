# 哈尔滨工程大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `hrbeu`
- Namespace Name: `哈尔滨工程大学`
- Route Path: `/hrbeu/yjsy/list/:id`
- Route Name: `研究生院`
- Example: `/hrbeu/yjsy/list/2981`
- URL: `yjsy.hrbeu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Derekmini`
- Source Location: `yjsy/list.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 新闻动态 | 学籍注册 | 奖助学金 | 其他 |
| :------: | :------: | :------: | :------: | :--: |
|   2981   |   2980   |   3009   |   3011   |  ... |

## Parameters
- `id`: 栏目编号，由 `URL` 中获取。


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
  - `yjsy.hrbeu.edu.cn/:id/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 新闻动态 | 学籍注册 | 奖助学金 | 其他 |\n| :------: | :------: | :------: | :------: | :--: |\n|   2981   |   2980   |   3009   |   3011   |  ... |",
  "example": "/hrbeu/yjsy/list/2981",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "yjsy/list.ts",
  "maintainers": [
    "Derekmini"
  ],
  "name": "研究生院",
  "parameters": {
    "id": "栏目编号，由 `URL` 中获取。"
  },
  "path": "/yjsy/list/:id",
  "radar": [
    {
      "source": [
        "yjsy.hrbeu.edu.cn/:id/list.htm"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "研究生院-通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84175752054718464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://yjsy.hrbeu.edu.cn/2981/list.htm",
      "title": "研究生院-通知公告",
      "type": "feed",
      "url": "rsshub://hrbeu/yjsy/list/2981"
    }
  ]
}
```
