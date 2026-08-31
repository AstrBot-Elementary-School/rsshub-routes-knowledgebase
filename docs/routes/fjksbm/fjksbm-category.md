# 福建考试报名网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `fjksbm`
- Namespace Name: `福建考试报名网`
- Route Path: `/fjksbm/:category?`
- Route Name: `分类`
- Example: `/fjksbm`
- URL: `fjksbm.com`
- Language: `_None_`
- Categories: `study`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 已发布公告 (方案)，即将开始 | 网络报名进行中 | 网络报名结束等待打印准考证 | 正在打印准考证 | 考试结束，等待发布成绩 | 已发布成绩 | 新闻动态 | 政策法规 |
| --------------------------- | -------------- | -------------------------- | -------------- | ---------------------- | ---------- | -------- | -------- |
| 0                           | 1              | 2                          | 3              | 4                      | 5          | news     | policy   |

## Parameters
- `category`: 分类，见下表，默认为网络报名进行中


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
  - `fjksbm.com/portal/:category?`
  - `fjksbm.com/portal`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "| 已发布公告 (方案)，即将开始 | 网络报名进行中 | 网络报名结束等待打印准考证 | 正在打印准考证 | 考试结束，等待发布成绩 | 已发布成绩 | 新闻动态 | 政策法规 |\n| --------------------------- | -------------- | -------------------------- | -------------- | ---------------------- | ---------- | -------- | -------- |\n| 0                           | 1              | 2                          | 3              | 4                      | 5          | news     | policy   |",
  "example": "/fjksbm",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为网络报名进行中"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "fjksbm.com/portal/:category?",
        "fjksbm.com/portal"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "已发布成绩 - 福建考试报名网 - Powered by RSSHub",
      "errorAt": "2025-02-01T09:36:31.707Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "74652091293119488",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://fjksbm.com/portal",
      "title": "已发布成绩 - 福建考试报名网",
      "type": "feed",
      "url": "rsshub://fjksbm"
    },
    {
      "description": null,
      "errorAt": "2025-06-01T11:07:39.146Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "151955931879114753",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://fjksbm/0"
    }
  ]
}
```
