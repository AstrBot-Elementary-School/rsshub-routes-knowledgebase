# 差评 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `chaping`
- Namespace Name: `差评`
- Route Path: `/chaping/news/:caty?`
- Route Name: `资讯`
- Example: `/chaping/news/15`
- URL: `chaping.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 编号 | 分类       |
| ---- | ---------- |
| 15   | 直播       |
| 3    | 科技新鲜事 |
| 7    | 互联网槽点 |
| 5    | 趣味科技   |
| 6    | DEBUG TIME |
| 1    | 游戏       |
| 8    | 视频       |
| 9    | 公里每小时 |

## Parameters
- `caty`: 分类，默认为全部资讯


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 编号 | 分类       |\n| ---- | ---------- |\n| 15   | 直播       |\n| 3    | 科技新鲜事 |\n| 7    | 互联网槽点 |\n| 5    | 趣味科技   |\n| 6    | DEBUG TIME |\n| 1    | 游戏       |\n| 8    | 视频       |\n| 9    | 公里每小时 |",
  "example": "/chaping/news/15",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 551,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "资讯",
  "parameters": {
    "caty": "分类，默认为全部资讯"
  },
  "path": "/news/:caty?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "差评资讯 - undefined - Powered by RSSHub",
      "errorAt": "2025-05-10T23:17:54.110Z",
      "errorMessage": "[GET] \"https://chaping.cn/api/official/information/news?page=1&limit=16&cate=\": 502 Bad Gateway\n",
      "id": "61432264574446592",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://chaping.cn/news?cate=",
      "title": "差评资讯 - undefined",
      "type": "feed",
      "url": "rsshub://chaping/news"
    },
    {
      "description": "差评资讯 - 科技新鲜事 - Powered by RSSHub",
      "errorAt": "2025-05-11T04:02:59.828Z",
      "errorMessage": "[GET] \"https://chaping.cn/api/official/information/news?page=1&limit=16&cate=3\": 502 Bad Gateway\n[GET] \"https://chaping.cn/api/official/information/news?page=1&limit=16&cate=3\": 502 Bad Gateway\n",
      "id": "59933051315126274",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://chaping.cn/news?cate=3",
      "title": "差评资讯 - 科技新鲜事",
      "type": "feed",
      "url": "rsshub://chaping/news/3"
    }
  ]
}
```
