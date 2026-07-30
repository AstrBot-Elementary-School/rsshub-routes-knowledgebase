# Deepin - 首页主题列表

## Coverage
`index-only`

## Route
- Namespace: `deepin`
- Namespace Name: `Deepin`
- Route Path: `/deepin/threads/:type?`
- Route Name: `首页主题列表`
- Example: `/deepin/threads/latest`
- URL: `bbs.deepin.org`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `myml`
- Source Location: `thread.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"description": "主题类型", "options": [{"label": "最热主题", "value": "hot"}, {"label": "最新主题", "value": "latest"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `bbs.deepin.org`
- `target`: `/threads/latest`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/deepin/threads/latest",
  "heat": 20,
  "location": "thread.ts",
  "maintainers": [
    "myml"
  ],
  "name": "首页主题列表",
  "parameters": {
    "type": {
      "description": "主题类型",
      "options": [
        {
          "label": "最热主题",
          "value": "hot"
        },
        {
          "label": "最新主题",
          "value": "latest"
        }
      ]
    }
  },
  "path": "/threads/:type?",
  "radar": [
    {
      "source": [
        "bbs.deepin.org"
      ],
      "target": "/threads/latest"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "deepin论坛主页 - 最新主题 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62087080975204352",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.deepin.org/",
      "title": "deepin论坛主页 - 最新主题",
      "type": "feed",
      "url": "rsshub://deepin/threads/latest"
    },
    {
      "description": "deepin论坛主页 - 最新主题 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "155304200635561984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.deepin.org/",
      "title": "deepin论坛主页 - 最新主题",
      "type": "feed",
      "url": "rsshub://deepin/threads"
    }
  ]
}
```
