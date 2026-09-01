# 登链社区 - 文章

## Coverage
`index-only`

## Route
- Namespace: `learnblockchain`
- Namespace Name: `登链社区`
- Route Path: `/learnblockchain/posts/:cid/:sort?`
- Route Name: `文章`
- Example: `/learnblockchain/posts/DApp/newest`
- URL: `learnblockchain.cn`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `running-grass`
- Source Location: `posts.ts`
- Source Module: `_None_`

## Description
| id       | 分类         |
| -------- | ------------ |
| all      | 全部         |
| DApp     | 去中心化应用 |
| chains   | 公链         |
| 联盟链   | 联盟链       |
| scaling  | Layer2       |
| langs    | 编程语言     |
| security | 安全         |
| dst      | 存储         |
| basic    | 理论研究     |
| other    | 其他         |

| id       | 排序方式    |
| -------- | ----------- |
| newest   | 最新        |
| featured | 精选 (默认) |
| featured | 最赞        |
| hottest  | 最热        |

## Parameters
- `cid`: 分类id,更多分类可以论坛的URL找到
- `sort`: 排序方式，默认精选


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
    "programming"
  ],
  "description": "| id       | 分类         |\n| -------- | ------------ |\n| all      | 全部         |\n| DApp     | 去中心化应用 |\n| chains   | 公链         |\n| 联盟链   | 联盟链       |\n| scaling  | Layer2       |\n| langs    | 编程语言     |\n| security | 安全         |\n| dst      | 存储         |\n| basic    | 理论研究     |\n| other    | 其他         |\n\n| id       | 排序方式    |\n| -------- | ----------- |\n| newest   | 最新        |\n| featured | 精选 (默认) |\n| featured | 最赞        |\n| hottest  | 最热        |",
  "example": "/learnblockchain/posts/DApp/newest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 40,
  "location": "posts.ts",
  "maintainers": [
    "running-grass"
  ],
  "name": "文章",
  "parameters": {
    "cid": "分类id,更多分类可以论坛的URL找到",
    "sort": "排序方式，默认精选"
  },
  "path": "/posts/:cid/:sort?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "登链社区 - Powered by RSSHub",
      "errorAt": "2026-06-11T03:26:27.499Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "62048478212359168",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://learnblockchain.cn/categories/all/newest/",
      "title": "登链社区--all",
      "type": "feed",
      "url": "rsshub://learnblockchain/posts/all/newest"
    },
    {
      "description": "登链社区 - Powered by RSSHub",
      "errorAt": "2026-05-30T06:55:21.917Z",
      "errorMessage": "Failed to fetch\n",
      "id": "61645117732882432",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://learnblockchain.cn/categories/DApp/newest/",
      "title": "登链社区--DApp",
      "type": "feed",
      "url": "rsshub://learnblockchain/posts/DApp/newest"
    }
  ]
}
```
