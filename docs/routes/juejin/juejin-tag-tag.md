# 掘金 - 标签

## Coverage
`index-only`

## Route
- Namespace: `juejin`
- Namespace Name: `掘金`
- Route Path: `/juejin/tag/:tag`
- Route Name: `标签`
- Example: `/juejin/tag/JavaScript`
- URL: `juejin.cn`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `isheng5`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tag`: 标签名，可在标签 URL 中找到


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
  - `juejin.cn/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/juejin/tag/JavaScript",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 572,
  "location": "tag.ts",
  "maintainers": [
    "isheng5"
  ],
  "name": "标签",
  "parameters": {
    "tag": "标签名，可在标签 URL 中找到"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "juejin.cn/tag/:tag"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "掘金 Java - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56924086186845184",
      "image": "https://p1-jj.byteimg.com/tos-cn-i-t2oaga2asx/leancloud-assets/f8ee3cd45f949a546263.png~tplv-t2oaga2asx-image.image",
      "ownerUserId": null,
      "siteUrl": "https://juejin.cn/tag/Java",
      "title": "掘金 Java",
      "type": "feed",
      "url": "rsshub://juejin/tag/Java"
    },
    {
      "description": "掘金 Flutter - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "53331456884697118",
      "image": "https://p1-jj.byteimg.com/tos-cn-i-t2oaga2asx/gold-user-assets/1519790365175e2d3ba2174d5c8f3fdc4687a8bbf5768.jpg~tplv-t2oaga2asx-image.image",
      "ownerUserId": null,
      "siteUrl": "https://juejin.cn/tag/Flutter",
      "title": "掘金 Flutter",
      "type": "feed",
      "url": "rsshub://juejin/tag/Flutter"
    }
  ]
}
```
