# 深圳证券交易所 - 问询函件

## Coverage
`index-only`

## Route
- Namespace: `szse`
- Namespace Name: `深圳证券交易所`
- Route Path: `/szse/inquire/:category?/:select?/:keyword?`
- Route Name: `问询函件`
- Example: `/szse/inquire`
- URL: `szse.cn/disclosure/supervision/inquire/index.html`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `Jeason0228, nczitzk`
- Source Location: `inquire.tsx`
- Source Module: `_None_`

## Description
类型

| 主板 | 创业板 |
| ---- | ------ |
| 0    | 1      |

函件类别

| 全部函件类别 | 非许可类重组问询函 | 问询函 | 违法违规线索分析报告 | 许可类重组问询函 | 监管函（会计师事务所模板） | 提请关注函（会计师事务所模板） | 年报问询函 | 向中介机构发函 | 半年报问询函 | 关注函 | 公司部函 | 三季报问询函 |
| ------------ | ------------------ | ------ | -------------------- | ---------------- | -------------------------- | ------------------------------ | ---------- | -------------- | ------------ | ------ | -------- | ------------ |

## Parameters
- `category`: 类型，见下表，默认为 `0` 即 主板
- `select`: 函件类别, 见下表，默认为全部函件类别
- `keyword`: 公司代码或简称，默认为空


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
  - `szse.cn/disclosure/supervision/inquire/index.html`
  - `szse.cn/`
- `target`: `/inquire`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "类型\n\n| 主板 | 创业板 |\n| ---- | ------ |\n| 0    | 1      |\n\n函件类别\n\n| 全部函件类别 | 非许可类重组问询函 | 问询函 | 违法违规线索分析报告 | 许可类重组问询函 | 监管函（会计师事务所模板） | 提请关注函（会计师事务所模板） | 年报问询函 | 向中介机构发函 | 半年报问询函 | 关注函 | 公司部函 | 三季报问询函 |\n| ------------ | ------------------ | ------ | -------------------- | ---------------- | -------------------------- | ------------------------------ | ---------- | -------------- | ------------ | ------ | -------- | ------------ |",
  "example": "/szse/inquire",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 20,
  "location": "inquire.tsx",
  "maintainers": [
    "Jeason0228",
    "nczitzk"
  ],
  "name": "问询函件",
  "parameters": {
    "category": "类型，见下表，默认为 `0` 即 主板",
    "keyword": "公司代码或简称，默认为空",
    "select": "函件类别, 见下表，默认为全部函件类别"
  },
  "path": "/inquire/:category?/:select?/:keyword?",
  "radar": [
    {
      "source": [
        "szse.cn/disclosure/supervision/inquire/index.html",
        "szse.cn/"
      ],
      "target": "/inquire"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "函件类别：全部函件类别 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64306740998267904",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.szse.cn/disclosure/supervision/inquire/index.html",
      "title": "深圳证券交易所 - 问询函件 - 主板",
      "type": "feed",
      "url": "rsshub://szse/inquire"
    },
    {
      "description": "函件类别：全部函件类别 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "112163264912778240",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.szse.cn/disclosure/supervision/inquire/index.html",
      "title": "深圳证券交易所 - 问询函件 - 创业板",
      "type": "feed",
      "url": "rsshub://szse/inquire/1"
    }
  ],
  "url": "szse.cn/disclosure/supervision/inquire/index.html"
}
```
