# 北京证券交易所 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `bse`
- Namespace Name: `北京证券交易所`
- Route Path: `/bse/:category?/:keyword?`
- Route Name: `栏目`
- Example: `/bse`
- URL: `bse.cn/`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 本所要闻        | 人才招聘 | 采购信息 | 业务通知   |
| --------------- | -------- | -------- | ---------- |
| important\_news | recruit  | purchase | news\_list |

| 法律法规  | 公开征求意见    | 部门规章         | 发行融资   |
| --------- | --------------- | ---------------- | ---------- |
| law\_list | public\_opinion | regulation\_list | fxrz\_list |

| 持续监管   | 交易管理   | 市场管理   | 上市委会议公告  |
| ---------- | ---------- | ---------- | --------------- |
| cxjg\_list | jygl\_list | scgl\_list | meeting\_notice |

| 上市委会议结果公告 | 上市委会议变更公告 | 并购重组委会议公告 |
| ------------------ | ------------------ | ------------------ |
| meeting\_result    | meeting\_change    | bgcz\_notice       |

| 并购重组委会议结果公告 | 并购重组委会议变更公告 | 终止审核           | 注册结果      |
| ---------------------- | ---------------------- | ------------------ | ------------- |
| bgcz\_result           | bgcz\_change           | termination\_audit | audit\_result |

## Parameters
- `category`: 分类，见下表，默认为本所要闻
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
  - `bse.cn/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 本所要闻        | 人才招聘 | 采购信息 | 业务通知   |\n| --------------- | -------- | -------- | ---------- |\n| important\\_news | recruit  | purchase | news\\_list |\n\n| 法律法规  | 公开征求意见    | 部门规章         | 发行融资   |\n| --------- | --------------- | ---------------- | ---------- |\n| law\\_list | public\\_opinion | regulation\\_list | fxrz\\_list |\n\n| 持续监管   | 交易管理   | 市场管理   | 上市委会议公告  |\n| ---------- | ---------- | ---------- | --------------- |\n| cxjg\\_list | jygl\\_list | scgl\\_list | meeting\\_notice |\n\n| 上市委会议结果公告 | 上市委会议变更公告 | 并购重组委会议公告 |\n| ------------------ | ------------------ | ------------------ |\n| meeting\\_result    | meeting\\_change    | bgcz\\_notice       |\n\n| 并购重组委会议结果公告 | 并购重组委会议变更公告 | 终止审核           | 注册结果      |\n| ---------------------- | ---------------------- | ------------------ | ------------- |\n| bgcz\\_result           | bgcz\\_change           | termination\\_audit | audit\\_result |",
  "example": "/bse",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "栏目",
  "parameters": {
    "category": "分类，见下表，默认为本所要闻",
    "keyword": "关键字，默认为空"
  },
  "path": "/:category?/:keyword?",
  "radar": [
    {
      "source": [
        "bse.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "bse.cn/"
}
```
