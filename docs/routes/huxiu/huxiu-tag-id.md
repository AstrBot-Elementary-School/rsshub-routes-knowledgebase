# 虎嗅 - 标签

## Coverage
`index-only`

## Route
- Namespace: `huxiu`
- Namespace Name: `虎嗅`
- Route Path: `/huxiu/tag/:id`
- Route Name: `标签`
- Example: `/huxiu/tag/291`
- URL: `huxiu.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `xyqfer, HenryQW, nczitzk, TimoYoung`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
更多标签请参见 [标签](https://www.huxiu.com/tags)

## Parameters
- `id`: 标签 id，可在对应标签页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "更多标签请参见 [标签](https://www.huxiu.com/tags)",
  "example": "/huxiu/tag/291",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 19,
  "location": "tag.ts",
  "maintainers": [
    "xyqfer",
    "HenryQW",
    "nczitzk",
    "TimoYoung"
  ],
  "name": "标签",
  "parameters": {
    "id": "标签 id，可在对应标签页 URL 中找到"
  },
  "path": "/tag/:id",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "人工智能的英文简称 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "111032291110780928",
      "image": "",
      "ownerUserId": null,
      "siteUrl": "https://www.huxiu.com/tag/10761.html",
      "title": "虎嗅标签-AI",
      "type": "feed",
      "url": "rsshub://huxiu/tag/10761"
    },
    {
      "description": "虎嗅标签-日本 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "126557871055055872",
      "image": "https://img.huxiucdn.com/tag/201507/17/170023452331.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.huxiu.com/tag/689.html",
      "title": "虎嗅标签-日本",
      "type": "feed",
      "url": "rsshub://huxiu/tag/689"
    }
  ]
}
```
