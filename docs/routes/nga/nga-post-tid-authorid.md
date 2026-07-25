# NGA - 帖子

## Coverage
`index-only`

## Route
- Namespace: `nga`
- Namespace Name: `NGA`
- Route Path: `/nga/post/:tid/:authorId?`
- Route Name: `帖子`
- Example: `/nga/post/18449558`
- URL: `bbs.nga.cn`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `xyqfer, syrinka`
- Source Location: `post.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tid`: 帖子 id, 可在帖子 URL 找到
- `authorId`: 作者 id


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
    "bbs"
  ],
  "example": "/nga/post/18449558",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 31,
  "location": "post.ts",
  "maintainers": [
    "xyqfer",
    "syrinka"
  ],
  "name": "帖子",
  "parameters": {
    "authorId": "作者 id",
    "tid": "帖子 id, 可在帖子 URL 找到"
  },
  "path": "/post/:tid/:authorId?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "NGA 牛找到了 在 - 上班很无聊，弄个实盘聊聊天 - 中的回复 178 - Powered by RSSHub",
      "errorAt": "2026-07-16T20:41:12.389Z",
      "errorMessage": "Cannot read properties of null (reading 'match')\n",
      "id": "154777115123643392",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nga.178.com/read.php?tid=41073656&page=120&authorid=66025368&rand=70.05172382970682#",
      "title": "NGA 牛找到了 在 - 上班很无聊，弄个实盘聊聊天 - 中的回复 178",
      "type": "feed",
      "url": "rsshub://nga/post/41073656/66025368"
    },
    {
      "description": "NGA -阿狼- 在 - 我必不是蛇年红包 - 中的回复 178 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "179409436734540800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nga.178.com/read.php?tid=43098323&page=292&authorid=150058&rand=445.62803900765755#",
      "title": "NGA -阿狼- 在 - 我必不是蛇年红包 - 中的回复 178",
      "type": "feed",
      "url": "rsshub://nga/post/43098323/150058"
    }
  ]
}
```
