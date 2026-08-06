# 西北师范大学 - 计算机科学与工程学院

## Coverage
`index-only`

## Route
- Namespace: `nwnu`
- Namespace Name: `西北师范大学`
- Route Path: `/nwnu/college/csse/:column`
- Route Name: `计算机科学与工程学院`
- Example: `/nwnu/college/csse/2435`
- URL: `www.nwnu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `PrinOrange`
- Source Location: `routes/college/csse.ts`
- Source Module: `_None_`

## Description
| column | 标题       | 描述                                          |
| ------ | ---------- | --------------------------------------------- |
| 2435   | 学院新闻   | 计算机科学与工程 学院新闻                     |
| 2436   | 通知公告   | 计算机科学与工程 通知公告                     |
| 2437   | 学术动态   | 计算机科学与工程 学术动态                     |
| 2446   | 研究生招生 | 计算机科学与工程学院 研究生招生动态及相关新闻 |
| 8411   | 评估动态   | 计算机科学与工程学院 院系学科评估动态         |

## Parameters
_None_


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
  - `jsj.nwnu.edu.cn/:column/list`
- `target`: `/college/csse/:column`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| column | 标题       | 描述                                          |\n| ------ | ---------- | --------------------------------------------- |\n| 2435   | 学院新闻   | 计算机科学与工程 学院新闻                     |\n| 2436   | 通知公告   | 计算机科学与工程 通知公告                     |\n| 2437   | 学术动态   | 计算机科学与工程 学术动态                     |\n| 2446   | 研究生招生 | 计算机科学与工程学院 研究生招生动态及相关新闻 |\n| 8411   | 评估动态   | 计算机科学与工程学院 院系学科评估动态         |",
  "example": "/nwnu/college/csse/2435",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "routes/college/csse.ts",
  "maintainers": [
    "PrinOrange"
  ],
  "name": "计算机科学与工程学院",
  "path": "/college/csse/:column",
  "radar": [
    {
      "source": [
        "jsj.nwnu.edu.cn/:column/list"
      ],
      "target": "/college/csse/:column"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "计算机科学与工程 学术动态 - Powered by RSSHub",
      "errorAt": "2025-10-29T11:02:40.922Z",
      "errorMessage": "[GET] \"https://jsj.nwnu.edu.cn/2437/list.htm\": 412 Precondition Failed\n",
      "id": "130515236979421184",
      "image": "https://jsj.nwnu.edu.cn/_upload/tpl/02/2e/558/template558/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://jsj.nwnu.edu.cn/2437/list.htm",
      "title": "学术动态",
      "type": "feed",
      "url": "rsshub://nwnu/college/csse/2437"
    },
    {
      "description": "计算机科学与工程 通知公告 - Powered by RSSHub",
      "errorAt": "2026-04-07T10:36:16.502Z",
      "errorMessage": "[GET] \"https://jsj.nwnu.edu.cn/2436/list.htm\": 412 Precondition Failed\n",
      "id": "130511119435133952",
      "image": "https://jsj.nwnu.edu.cn/_upload/tpl/02/2e/558/template558/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://jsj.nwnu.edu.cn/2436/list.htm",
      "title": "通知公告",
      "type": "feed",
      "url": "rsshub://nwnu/college/csse/2436"
    }
  ]
}
```
