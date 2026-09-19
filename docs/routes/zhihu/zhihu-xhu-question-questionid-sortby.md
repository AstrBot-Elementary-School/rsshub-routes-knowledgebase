# 知乎 - xhu - 问题

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/xhu/question/:questionId/:sortBy?`
- Route Name: `xhu - 问题`
- Example: `/zhihu/xhu/question/264051433`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `JimenezLi`
- Source Location: `xhu/question.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `questionId`: 问题 id
- `sortBy`: 排序方式：`default`, `created`, `updated`。默认为 `default`


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
  - `www.zhihu.com/question/:questionId`
- `target`: `/xhu/question/:questionId`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/xhu/question/264051433",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "xhu/question.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "name": "xhu - 问题",
  "parameters": {
    "questionId": "问题 id",
    "sortBy": "排序方式：`default`, `created`, `updated`。默认为 `default`"
  },
  "path": "/xhu/question/:questionId/:sortBy?",
  "radar": [
    {
      "source": [
        "www.zhihu.com/question/:questionId"
      ],
      "target": "/xhu/question/:questionId"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "知乎-哪一刻让你觉得世人皆苦? - Powered by RSSHub",
      "errorAt": "2025-02-12T07:42:54.741Z",
      "errorMessage": "[GET] \"https://api.zhihuvvv.workers.dev/guests/token\": 401 Unauthorized\n",
      "id": "87791692985956352",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/question/281271203",
      "title": "知乎-哪一刻让你觉得世人皆苦?",
      "type": "feed",
      "url": "rsshub://zhihu/xhu/question/281271203"
    },
    {
      "description": "知乎-体制内不想提拔是不是就近似无敌了？ - Powered by RSSHub",
      "errorAt": "2025-07-21T18:29:00.439Z",
      "errorMessage": "[GET] \"https://api.zhihuvvv.workers.dev/guests/token\": 401 Unauthorized\n",
      "id": "87789825695128576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/question/576151137",
      "title": "知乎-体制内不想提拔是不是就近似无敌了？",
      "type": "feed",
      "url": "rsshub://zhihu/xhu/question/576151137"
    }
  ]
}
```
