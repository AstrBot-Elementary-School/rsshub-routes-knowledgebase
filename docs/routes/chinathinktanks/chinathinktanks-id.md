# 中国智库网 - 观点与实践

## Coverage
`index-only`

## Route
- Namespace: `chinathinktanks`
- Namespace Name: `中国智库网`
- Route Path: `/chinathinktanks/:id`
- Route Name: `观点与实践`
- Example: `/chinathinktanks/57`
- URL: `www.chinathinktanks.org.cn`
- Language: `_None_`
- Categories: `study`
- Maintainers: `Aeliu`
- Source Location: `viewpoint.ts`
- Source Module: `_None_`

## Description
网站已迁移，其他旧数字分类已下线，请使用新版分类 URL 中的 UUID。

| id                                   | 分类     |
| ------------------------------------ | -------- |
| 87e1e7e4-ffcb-401d-aa8a-c086b9eccec1 | 智库资讯 |
| 54a1eca3-4e67-464d-bad3-eae6ac25c96a | 研究成果 |
| 4e93db34-5604-41c0-96e7-51dcebcf6735 | 全球经济 |
| 74af5bf8-131d-4b73-b7ec-83013608388e | 调研数据 |

## Parameters
- `id`: 新版网站分类 URL 中的 UUID，见下表。旧 id 57、46 分别保留为智库资讯、研究报告。


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
    "study"
  ],
  "description": "网站已迁移，其他旧数字分类已下线，请使用新版分类 URL 中的 UUID。\n\n| id                                   | 分类     |\n| ------------------------------------ | -------- |\n| 87e1e7e4-ffcb-401d-aa8a-c086b9eccec1 | 智库资讯 |\n| 54a1eca3-4e67-464d-bad3-eae6ac25c96a | 研究成果 |\n| 4e93db34-5604-41c0-96e7-51dcebcf6735 | 全球经济 |\n| 74af5bf8-131d-4b73-b7ec-83013608388e | 调研数据 |",
  "example": "/chinathinktanks/57",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 31,
  "location": "viewpoint.ts",
  "maintainers": [
    "Aeliu"
  ],
  "name": "观点与实践",
  "parameters": {
    "id": "新版网站分类 URL 中的 UUID，见下表。旧 id 57、46 分别保留为智库资讯、研究报告。"
  },
  "path": "/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "中国智库网 —— 国外智库 - Powered by RSSHub",
      "errorAt": "2025-12-31T21:07:15.108Z",
      "errorMessage": "[GET] \"https://www.chinathinktanks.org.cn/content/list?id=13&pt=1\": 404 Not Found\n",
      "id": "75371518748737536",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.chinathinktanks.org.cn/content/list?id=13&pt=1",
      "title": "中国智库网 —— 国外智库",
      "type": "feed",
      "url": "rsshub://chinathinktanks/13"
    },
    {
      "description": "中国智库网 —— 智库要闻 - Powered by RSSHub",
      "errorAt": "2026-01-01T08:00:14.789Z",
      "errorMessage": "[GET] \"https://www.chinathinktanks.org.cn/content/list?id=57&pt=1\": <no response> fetch failed (Client network socket disconnected before secure TLS connection was established)\n[GET] \"https://www.chinathinktanks.org.cn/content/list?id=57&pt=1\": 525 <none>\n",
      "id": "63858618178298974",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.chinathinktanks.org.cn/content/list?id=57&pt=1",
      "title": "中国智库网 —— 智库要闻",
      "type": "feed",
      "url": "rsshub://chinathinktanks/57"
    }
  ]
}
```
