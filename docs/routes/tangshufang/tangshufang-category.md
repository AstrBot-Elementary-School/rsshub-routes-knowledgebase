# 唐书房 - 分类

## Coverage
`index-only`

## Route
- Namespace: `tangshufang`
- Namespace Name: `唐书房`
- Route Path: `/tangshufang/:category?`
- Route Name: `分类`
- Example: `/tangshufang`
- URL: `tangshufang.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 首页 | 老唐实盘 | 书房拾遗 | 理念 & 估值 | 经典陪读 | 财务套利 |
| ---- | -------- | -------- | ----------- | -------- | -------- |
|      | shipan   | wenda    | linian      | peidu    | taoli    |

| 企业分析 | 白酒企业 | 腾讯控股 | 分众传媒 | 海康威视 | 其他企业 |
| -------- | -------- | -------- | -------- | -------- | -------- |
| qiye     | baijiu   | tengxun  | fenzhong | haikang  | qita     |

| 核心五篇 | 读者投稿 | 读书随笔 | 财报浅析 | 出行游记 | 巴芒连载 |
| -------- | -------- | -------- | -------- | -------- | -------- |
| hexin    | tougao   | suibi    | caibao   | youji    | bamang   |

## Parameters
- `category`: 分类，见下表，默认为首页


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
  - `tangshufang.com/:category`
  - `tangshufang.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 首页 | 老唐实盘 | 书房拾遗 | 理念 & 估值 | 经典陪读 | 财务套利 |\n| ---- | -------- | -------- | ----------- | -------- | -------- |\n|      | shipan   | wenda    | linian      | peidu    | taoli    |\n\n| 企业分析 | 白酒企业 | 腾讯控股 | 分众传媒 | 海康威视 | 其他企业 |\n| -------- | -------- | -------- | -------- | -------- | -------- |\n| qiye     | baijiu   | tengxun  | fenzhong | haikang  | qita     |\n\n| 核心五篇 | 读者投稿 | 读书随笔 | 财报浅析 | 出行游记 | 巴芒连载 |\n| -------- | -------- | -------- | -------- | -------- | -------- |\n| hexin    | tougao   | suibi    | caibao   | youji    | bamang   |",
  "example": "/tangshufang",
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
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为首页"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "tangshufang.com/:category",
        "tangshufang.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
