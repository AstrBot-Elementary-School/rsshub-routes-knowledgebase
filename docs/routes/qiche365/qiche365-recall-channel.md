# 汽车召回网 - 汽车召回

## Coverage
`index-only`

## Route
- Namespace: `qiche365`
- Namespace Name: `汽车召回网`
- Route Path: `/qiche365/recall/:channel`
- Route Name: `汽车召回`
- Example: `/qiche365/recall/1`
- URL: `qiche365.org.cn/index/recall/index.html`
- Language: `_None_`
- Categories: `government`
- Maintainers: `huanfe1, pseudoyu`
- Source Location: `recall.ts`
- Source Module: `_None_`

## Description
| 国内召回新闻 | 国内召回公告 | 国外召回新闻 | 国外召回公告 |
| ------------ | ------------ | ------------ | ------------ |
| 1            | 2            | 3            | 4            |

## Parameters
- `channel`: 频道，见下表


## Features
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 国内召回新闻 | 国内召回公告 | 国外召回新闻 | 国外召回公告 |\n| ------------ | ------------ | ------------ | ------------ |\n| 1            | 2            | 3            | 4            |",
  "example": "/qiche365/recall/1",
  "features": {
    "antiCrawler": true
  },
  "heat": 52,
  "location": "recall.ts",
  "maintainers": [
    "huanfe1",
    "pseudoyu"
  ],
  "name": "汽车召回",
  "parameters": {
    "channel": "频道，见下表"
  },
  "path": "/recall/:channel",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "国内召回公告 - Powered by RSSHub",
      "errorAt": "2026-05-29T14:52:55.418Z",
      "errorMessage": "[GET] \"https://www.qiche365.org.cn/index/recall/index/item/1.html?loadmore=1\": 403 Forbidden\n[GET] \"https://www.qiche365.org.cn/index/recall/index/item/1.html?loadmore=1\": <no response> fetch failed (other side closed)\n",
      "id": "60152580433969152",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.qiche365.org.cn/index/recall/index.html",
      "title": "国内召回公告",
      "type": "feed",
      "url": "rsshub://qiche365/recall/1"
    },
    {
      "description": "国外召回公告 - Powered by RSSHub",
      "errorAt": "2026-07-25T03:56:32.101Z",
      "errorMessage": "[GET] \"https://www.qiche365.org.cn/index/recall/index/item/3.html?loadmore=1\": 403 Forbidden\n[GET] \"https://www.qiche365.org.cn/index/recall/index/item/3.html?loadmore=1\": <no response> fetch failed (other side closed)\n",
      "id": "73385956001950720",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.qiche365.org.cn/index/recall/index.html",
      "title": "国外召回公告",
      "type": "feed",
      "url": "rsshub://qiche365/recall/3"
    }
  ],
  "url": "qiche365.org.cn/index/recall/index.html"
}
```
