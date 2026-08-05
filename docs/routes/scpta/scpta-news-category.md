# 四川省人力资源和社会保障厅人事考试专栏 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `scpta`
- Namespace Name: `四川省人力资源和社会保障厅人事考试专栏`
- Route Path: `/scpta/news/:category`
- Route Name: `通知公告`
- Example: `/scpta/news/33`
- URL: `www.scpta.com.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `Yeye-0426`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 分类                 | category\_id |
| -------------------- | ------------ |
| 工作动态             | 33           |
| 公务员考试           | 56           |
| 专业技术人员资格考试 | 57           |
| 事业单位考试         | 67           |
| 其它                 | 72           |

## Parameters
- `category`: {"default": "33", "description": "分类ID，默认为`33`(工作动态)"}


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
  - `www.scpta.com.cn/front/News/List`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 分类                 | category\\_id |\n| -------------------- | ------------ |\n| 工作动态             | 33           |\n| 公务员考试           | 56           |\n| 专业技术人员资格考试 | 57           |\n| 事业单位考试         | 67           |\n| 其它                 | 72           |",
  "example": "/scpta/news/33",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "news.ts",
  "maintainers": [
    "Yeye-0426"
  ],
  "name": "通知公告",
  "parameters": {
    "category": {
      "default": "33",
      "description": "分类ID，默认为`33`(工作动态)"
    }
  },
  "path": "/news/:category",
  "radar": [
    {
      "source": [
        "www.scpta.com.cn/front/News/List"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "通知公告 - 事业单位考试 - Powered by RSSHub",
      "errorAt": "2026-02-06T05:27:14.779Z",
      "errorMessage": "[GET] \"https://www.scpta.com.cn/front/News/List/67\": <no response> fetch failed (Connect Timeout Error (attempted address: www.scpta.com.cn:443, timeout: 10000ms))\n",
      "id": "178439059880655872",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.scpta.com.cn/front/News/List/67",
      "title": "通知公告 - 事业单位考试",
      "type": "feed",
      "url": "rsshub://scpta/news/67"
    },
    {
      "description": "通知公告 - 工作动态 - Powered by RSSHub",
      "errorAt": "2026-02-06T08:05:22.521Z",
      "errorMessage": "[GET] \"https://www.scpta.com.cn/front/News/List/33\": <no response> fetch failed (Connect Timeout Error (attempted address: www.scpta.com.cn:443, timeout: 10000ms))\n",
      "id": "178439478979079168",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.scpta.com.cn/front/News/List/33",
      "title": "通知公告 - 工作动态",
      "type": "feed",
      "url": "rsshub://scpta/news/33"
    }
  ]
}
```
