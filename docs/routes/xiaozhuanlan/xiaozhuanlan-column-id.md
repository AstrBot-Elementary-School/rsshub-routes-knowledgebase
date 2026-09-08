# 小专栏 - 专栏

## Coverage
`index-only`

## Route
- Namespace: `xiaozhuanlan`
- Namespace Name: `小专栏`
- Route Path: `/xiaozhuanlan/column/:id`
- Route Name: `专栏`
- Example: `/xiaozhuanlan/column/olddriver-selection`
- URL: `xiaozhuanlan.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `column.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 专栏 ID，可在专栏页 URL 中找到


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
  - `xiaozhuanlan.com/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/xiaozhuanlan/column/olddriver-selection",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "column.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "专栏",
  "parameters": {
    "id": "专栏 ID，可在专栏页 URL 中找到"
  },
  "path": "/column/:id",
  "radar": [
    {
      "source": [
        "xiaozhuanlan.com/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "WWDC24 内参 - @老司机技术 - 《WWDC24 内参》来啦。今年我们会继续和社区一起创作关于今年 WWDC24 的 Session 解读，敬请期待。 - Powered by RSSHub",
      "errorAt": "2025-06-07T04:15:50.159Z",
      "errorMessage": "[GET] \"https://xiaozhuanlan.com/wwdc24\": <no response> fetch failed (Connect Timeout Error (attempted address: xiaozhuanlan.com:443, timeout: 10000ms))\n",
      "id": "67025004373372928",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xiaozhuanlan.com/wwdc24",
      "title": "WWDC24 内参 － 小专栏",
      "type": "feed",
      "url": "rsshub://xiaozhuanlan/column/wwdc24"
    },
    {
      "description": "SwiftOldDriver 精选 - @没故事的卓同学 - 老司机 iOS 周报编辑们的私房原创文章，基于周报对一些知识点进行更全面、深入的展开，或者外文的翻译。 专栏文章每周一更，持续到 18 年底。 - Powered by RSSHub",
      "errorAt": "2025-06-07T04:31:47.648Z",
      "errorMessage": "[GET] \"https://xiaozhuanlan.com/olddriver-selection\": <no response> fetch failed (Connect Timeout Error (attempted address: xiaozhuanlan.com:443, timeout: 10000ms))\n",
      "id": "80490593077723136",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xiaozhuanlan.com/olddriver-selection",
      "title": "SwiftOldDriver 精选 － 小专栏",
      "type": "feed",
      "url": "rsshub://xiaozhuanlan/column/olddriver-selection"
    }
  ]
}
```
