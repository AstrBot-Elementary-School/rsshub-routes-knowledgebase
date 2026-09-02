# 机核网 - 播客

## Coverage
`index-only`

## Route
- Namespace: `gcores`
- Namespace Name: `机核网`
- Route Path: `/gcores/radios/:category?`
- Route Name: `播客`
- Example: `/gcores/radios/45`
- URL: `gcores.com/radios`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `eternasuno`
- Source Location: `radio.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: 分类名，默认为全部，可在分类页面的 URL 中找到，如 Gadio News -- 45


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `gcores.com/categories/:category`
- `target`: `/radios/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/gcores/radios/45",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 433,
  "location": "radio.tsx",
  "maintainers": [
    "eternasuno"
  ],
  "name": "播客",
  "parameters": {
    "category": "分类名，默认为全部，可在分类页面的 URL 中找到，如 Gadio News -- 45"
  },
  "path": "/radios/:category?",
  "radar": [
    {
      "source": [
        "gcores.com/categories/:category"
      ],
      "target": "/radios/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "收听机核播客节目，覆盖游戏文化、影视、科技、生活与创作者故事。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56687029497668608",
      "image": "https://www.gcores.com//apple-touch-icon.png?v=jw7pQOOwRY",
      "ownerUserId": null,
      "siteUrl": "https://www.gcores.com/radios",
      "title": "播客 | 机核 GCORES",
      "type": "feed",
      "url": "rsshub://gcores/radios"
    },
    {
      "description": "机核从2010年开始一直致力于分享游戏玩家的生活，以及深入探讨游戏相关的文化。我们开发原创的播客以及视频节目，一直在不断寻找民间高质量的内容创作者。 我们坚信游戏不止是游戏，游戏中包含的科学，文化，历史等各个层面的知识和故事，它们同时也会辐射到二次元甚至电影的领域，这些内容非常值得分享给热爱游戏的您。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59830706624122880",
      "image": "https://www.gcores.com//apple-touch-icon.png?v=jw7pQOOwRY",
      "ownerUserId": null,
      "siteUrl": "https://www.gcores.com/categories/45",
      "title": "GadioNews | 机核 GCORES",
      "type": "feed",
      "url": "rsshub://gcores/radios/45"
    }
  ],
  "url": "gcores.com/radios"
}
```
