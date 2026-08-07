# 一亩三分地 - 博客

## Coverage
`index-only`

## Route
- Namespace: `1point3acres`
- Namespace Name: `一亩三分地`
- Route Path: `/1point3acres/blog/:category?`
- Route Name: `博客`
- Example: `/1point3acres/blog`
- URL: `blog.1point3acres.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
| 留学申请   | 找工求职 | 生活攻略  | 投资理财 | 签证移民 | 时政要闻 |
| ---------- | -------- | --------- | -------- | -------- | -------- |
| studyinusa | career   | lifestyle | invest   | visa     | news     |

## Parameters
- `category`: 分类，见下表，可在对应分类页 URL 中找到


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
  - `blog.1point3acres.com/:category`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "| 留学申请   | 找工求职 | 生活攻略  | 投资理财 | 签证移民 | 时政要闻 |\n| ---------- | -------- | --------- | -------- | -------- | -------- |\n| studyinusa | career   | lifestyle | invest   | visa     | news     |",
  "example": "/1point3acres/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "blog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "博客",
  "parameters": {
    "category": "分类，见下表，可在对应分类页 URL 中找到"
  },
  "path": "/blog/:category?",
  "radar": [
    {
      "source": [
        "blog.1point3acres.com/:category"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "美国留学就业生活攻略 - Powered by RSSHub",
      "errorAt": "2026-07-16T19:11:56.919Z",
      "errorMessage": "[GET] \"https://blog.1point3acres.com/wp-json/wp/v2/posts?per_page=100\": 403 Forbidden\n",
      "id": "82671443591248896",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://blog.1point3acres.com/undefined/",
      "title": "美国留学就业生活攻略",
      "type": "feed",
      "url": "rsshub://1point3acres/blog"
    },
    {
      "description": "留学申请 | 美国留学就业生活攻略 - Powered by RSSHub",
      "errorAt": "2026-07-15T22:59:39.459Z",
      "errorMessage": "[GET] \"https://blog.1point3acres.com/wp-json/wp/v2/posts?categories=18&per_page=100\": 403 Forbidden\n",
      "id": "55160374844817408",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://blog.1point3acres.com/studyinusa/",
      "title": "留学申请 | 美国留学就业生活攻略",
      "type": "feed",
      "url": "rsshub://1point3acres/blog/studyinusa"
    }
  ]
}
```
