# PANews - 深度

## Coverage
`index-only`

## Route
- Namespace: `panewslab`
- Namespace Name: `PANews`
- Route Path: `/panewslab/profundity/:category?`
- Route Name: `深度`
- Example: `/panewslab/profundity`
- URL: `panewslab.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `profundity.ts`
- Source Module: `_None_`

## Description
| 精选 | 链游 | 元宇宙 | NFT | DeFi | 监管 | 央行数字货币 | 波卡 | Layer 2 | DAO | 融资 | 活动 |
| ---- | ---- | ------ | --- | ---- | ---- | ------------ | ---- | ------- | --- | ---- | ---- |

## Parameters
- `category`: 分类，见下表，默认为精选


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `panewslab.com/`
### Rule 2
- `source`:
  - `www.panewslab.com/zh/profundity/index.html`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 精选 | 链游 | 元宇宙 | NFT | DeFi | 监管 | 央行数字货币 | 波卡 | Layer 2 | DAO | 融资 | 活动 |\n| ---- | ---- | ------ | --- | ---- | ---- | ------------ | ---- | ------- | --- | ---- | ---- |",
  "example": "/panewslab/profundity",
  "heat": 132,
  "location": "profundity.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "深度",
  "parameters": {
    "category": "分类，见下表，默认为精选"
  },
  "path": "/profundity/:category?",
  "radar": [
    {
      "source": [
        "panewslab.com/"
      ]
    },
    {
      "source": [
        "www.panewslab.com/zh/profundity/index.html"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "PANews - 精选 - Powered by RSSHub",
      "errorAt": "2025-12-14T11:22:59.129Z",
      "errorMessage": "[GET] \"https://panewslab.com/webapi/depth/list?LId=1&Rn=25&TagId=&tw=0\": 404 Not Found\n",
      "id": "57477263957849088",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://panewslab.com/zh/profundity/index.html",
      "title": "PANews - 精选",
      "type": "feed",
      "url": "rsshub://panewslab/profundity"
    }
  ],
  "url": "panewslab.com/"
}
```
