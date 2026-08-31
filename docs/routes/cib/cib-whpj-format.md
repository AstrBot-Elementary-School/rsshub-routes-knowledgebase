# 中国兴业银行 - 外汇牌价

## Coverage
`index-only`

## Route
- Namespace: `cib`
- Namespace Name: `中国兴业银行`
- Route Path: `/cib/whpj/:format?`
- Route Name: `外汇牌价`
- Example: `/cib/whpj/xh?filter_title=USD`
- URL: `cib.com.cn/`
- Language: `_None_`
- Categories: `other`
- Maintainers: `Qixingchen`
- Source Location: `whpj.ts`
- Source Module: `_None_`

## Description
| 短格式 | 现汇买卖 | 现钞买卖 | 现汇买入 | 现汇卖出 | 现钞买入 | 现钞卖出 |
| ------ | -------- | -------- | -------- | -------- | -------- | -------- |
| short  | xh       | xc       | xhmr     | xhmc     | xcmr     | xcmc     |

## Parameters
- `format`: 输出的标题格式，默认为标题 + 所有价格。短格式仅包含货币名称。


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
  - `cib.com.cn/`
- `target`: `/whpj`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "| 短格式 | 现汇买卖 | 现钞买卖 | 现汇买入 | 现汇卖出 | 现钞买入 | 现钞卖出 |\n| ------ | -------- | -------- | -------- | -------- | -------- | -------- |\n| short  | xh       | xc       | xhmr     | xhmc     | xcmr     | xcmc     |",
  "example": "/cib/whpj/xh?filter_title=USD",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "whpj.ts",
  "maintainers": [
    "Qixingchen"
  ],
  "name": "外汇牌价",
  "parameters": {
    "format": "输出的标题格式，默认为标题 + 所有价格。短格式仅包含货币名称。"
  },
  "path": "/whpj/:format?",
  "radar": [
    {
      "source": [
        "cib.com.cn/"
      ],
      "target": "/whpj"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "cib.com.cn/"
}
```
