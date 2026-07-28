# PSN 中文站 - 节点

## Coverage
`index-only`

## Route
- Namespace: `psnine`
- Namespace Name: `PSN 中文站`
- Route Path: `/psnine/node/:id?/:order?`
- Route Name: `节点`
- Example: `/psnine/node/news`
- URL: `psnine.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `betta-cyber, nczitzk`
- Source Location: `node.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 节点 id，见下表，默认为 news
- `order`: 排序，`date` 即最新，默认为 `obdate` 即综合排序


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `psnine.com/node/:id`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/psnine/node/news",
  "heat": 4,
  "location": "node.ts",
  "maintainers": [
    "betta-cyber",
    "nczitzk"
  ],
  "name": "节点",
  "parameters": {
    "id": "节点 id，见下表，默认为 news",
    "order": "排序，`date` 即最新，默认为 `obdate` 即综合排序"
  },
  "path": "/node/:id?/:order?",
  "radar": [
    {
      "source": [
        "psnine.com/node/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "「会免」最新讨论 - PSN中文站 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "125916510049597440",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.psnine.com/node/plus?ob=obdate",
      "title": "「会免」最新讨论 - PSN中文站",
      "type": "feed",
      "url": "rsshub://psnine/node/plus"
    },
    {
      "description": "「新闻」最新讨论 - PSN中文站 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "130453375930870784",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.psnine.com/node/news?ob=obdate",
      "title": "「新闻」最新讨论 - PSN中文站",
      "type": "feed",
      "url": "rsshub://psnine/node/news"
    }
  ]
}
```
