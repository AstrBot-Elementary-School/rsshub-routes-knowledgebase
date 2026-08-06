# 西北师范大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `nwnu`
- Namespace Name: `西北师范大学`
- Route Path: `/nwnu/department/postgraduate/:column`
- Route Name: `研究生院`
- Example: `/nwnu/department/postgraduate/2701`
- URL: `www.nwnu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `PrinOrange`
- Source Location: `routes/department/postgraduate.ts`
- Source Module: `_None_`

## Description
| column | 标题                           | 描述                                               |
| ------ | ------------------------------ | -------------------------------------------------- |
| 2701   | 招生工作（包括硕士、博士招生） | 研究生院招生信息（包含硕士招生和博士招生两个栏目） |
| 2712   | 博士招生                       | 研究生院博士研究生招生信息                         |
| 2713   | 硕士招生                       | 研究生院硕士研究生招生信息                         |
| 2702   | 培养工作                       | 培养工作栏目信息汇总                               |
| 2703   | 学科建设                       | 研究生院学科建设信息汇总                           |
| 2704   | 学位工作                       | 研究生院学位工作栏目信息汇总                       |

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportRadar`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `yjsy.nwnu.edu.cn/:column/list.htm`
- `target`: `/department/postgraduate/:column`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| column | 标题                           | 描述                                               |\n| ------ | ------------------------------ | -------------------------------------------------- |\n| 2701   | 招生工作（包括硕士、博士招生） | 研究生院招生信息（包含硕士招生和博士招生两个栏目） |\n| 2712   | 博士招生                       | 研究生院博士研究生招生信息                         |\n| 2713   | 硕士招生                       | 研究生院硕士研究生招生信息                         |\n| 2702   | 培养工作                       | 培养工作栏目信息汇总                               |\n| 2703   | 学科建设                       | 研究生院学科建设信息汇总                           |\n| 2704   | 学位工作                       | 研究生院学位工作栏目信息汇总                       |",
  "example": "/nwnu/department/postgraduate/2701",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 2,
  "location": "routes/department/postgraduate.ts",
  "maintainers": [
    "PrinOrange"
  ],
  "name": "研究生院",
  "path": "/department/postgraduate/:column",
  "radar": [
    {
      "source": [
        "yjsy.nwnu.edu.cn/:column/list.htm"
      ],
      "target": "/department/postgraduate/:column"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "研究生院硕士研究生招生信息 - Powered by RSSHub",
      "errorAt": "2026-04-07T06:22:35.209Z",
      "errorMessage": "[GET] \"https://yjsy.nwnu.edu.cn/2713/list.htm\": 412 Precondition Failed\n",
      "id": "130512331000963072",
      "image": "https://www.nwnu.edu.cn/_upload/tpl/02/d9/729/template729/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://yjsy.nwnu.edu.cn/2713/list.htm",
      "title": "硕士招生",
      "type": "feed",
      "url": "rsshub://nwnu/department/postgraduate/2713"
    },
    {
      "description": "研究生院工作动态 - Powered by RSSHub",
      "errorAt": "2025-10-29T13:16:18.599Z",
      "errorMessage": "[GET] \"https://yjsy.nwnu.edu.cn/2738/list.htm\": 412 Precondition Failed\n",
      "id": "130513898874565632",
      "image": "https://www.nwnu.edu.cn/_upload/tpl/02/d9/729/template729/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://yjsy.nwnu.edu.cn/2738/list.htm",
      "title": "工作动态",
      "type": "feed",
      "url": "rsshub://nwnu/department/postgraduate/2738"
    }
  ]
}
```
