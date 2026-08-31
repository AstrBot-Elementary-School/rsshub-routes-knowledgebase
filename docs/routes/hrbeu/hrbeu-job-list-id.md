# 哈尔滨工程大学 - 就业服务平台

## Coverage
`index-only`

## Route
- Namespace: `hrbeu`
- Namespace Name: `哈尔滨工程大学`
- Route Path: `/hrbeu/job/list/:id`
- Route Name: `就业服务平台`
- Example: `/hrbeu/job/list/tzgg`
- URL: `yjsy.hrbeu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Derekmini`
- Source Location: `job/list.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 热点新闻 |
| :------: | :------: |
|   tzgg   |   rdxw   |

## Parameters
- `id`: 栏目，如下表


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
    "university"
  ],
  "description": "| 通知公告 | 热点新闻 |\n| :------: | :------: |\n|   tzgg   |   rdxw   |",
  "example": "/hrbeu/job/list/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "job/list.ts",
  "maintainers": [
    "Derekmini"
  ],
  "name": "就业服务平台",
  "parameters": {
    "id": "栏目，如下表"
  },
  "path": "/job/list/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "就业服务平台-通知公告 - Powered by RSSHub",
      "errorAt": "2025-08-08T11:32:14.258Z",
      "errorMessage": "[GET] \"http://job.hrbeu.edu.cn/HrbeuJY/Web/Home/NewsList?43kuJdqqW6kyCmomBv0smMlyGfDy8QefMwSyc-jK8Ww=.shtml\": 404 \n",
      "id": "77555267043885056",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://job.hrbeu.edu.cn/HrbeuJY/Web/Home/NewsList?43kuJdqqW6kyCmomBv0smMlyGfDy8QefMwSyc-jK8Ww=.shtml",
      "title": "就业服务平台-通知公告",
      "type": "feed",
      "url": "rsshub://hrbeu/job/list/tzgg"
    }
  ]
}
```
