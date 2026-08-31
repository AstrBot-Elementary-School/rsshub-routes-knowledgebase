# 消费者委员会 - 文章

## Coverage
`index-only`

## Route
- Namespace: `consumer`
- Namespace Name: `消费者委员会`
- Route Path: `/consumer/:category?/:language?/:keyword?`
- Route Name: `文章`
- Example: `/consumer`
- URL: `consumer.org.hk/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
分类

| 测试及调查 | 生活资讯 | 投诉实录  | 议题评论 |
| ---------- | -------- | --------- | -------- |
| test       | life     | complaint | topic    |

语言

| 简体中文 | 繁体中文 |
| -------- | -------- |
| sc       | tc       |

## Parameters
- `category`: 分类，见下表，默认为測試及調查
- `language`: 语言，见下表，默认为繁体中文
- `keyword`: 关键字，默认为空


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
  - `consumer.org.hk/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "分类\n\n| 测试及调查 | 生活资讯 | 投诉实录  | 议题评论 |\n| ---------- | -------- | --------- | -------- |\n| test       | life     | complaint | topic    |\n\n语言\n\n| 简体中文 | 繁体中文 |\n| -------- | -------- |\n| sc       | tc       |",
  "example": "/consumer",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "文章",
  "parameters": {
    "category": "分类，见下表，默认为測試及調查",
    "keyword": "关键字，默认为空",
    "language": "语言，见下表，默认为繁体中文"
  },
  "path": "/:category?/:language?/:keyword?",
  "radar": [
    {
      "source": [
        "consumer.org.hk/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "測試及調查 - 消費者委員會 - Powered by RSSHub",
      "errorAt": "2025-01-02T04:08:51.076Z",
      "errorMessage": "[GET] \"https://www.consumer.org.hk/tc/free-article/free-article-test?category=free-article-test&q=\": 404 Not Found\n",
      "id": "55295012804329472",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.consumer.org.hk/tc/free-article/free-article-test?category=free-article-test&q=",
      "title": "測試及調查 - 消費者委員會",
      "type": "feed",
      "url": "rsshub://consumer"
    }
  ],
  "url": "consumer.org.hk/"
}
```
