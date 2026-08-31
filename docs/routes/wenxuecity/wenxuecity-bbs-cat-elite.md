# 文学城 - 最新主题

## Coverage
`index-only`

## Route
- Namespace: `wenxuecity`
- Namespace Name: `文学城`
- Route Path: `/wenxuecity/bbs/:cat/:elite?`
- Route Name: `最新主题`
- Example: `/wenxuecity/bbs/tzlc`
- URL: `wenxuecity.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `changlan`
- Source Location: `bbs.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `cat`: 版面名, 可在 URL 中找到
- `elite`: 是否精华区, 1 为精华区


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `bbs.wenxuecity.com/:cat`
- `target`: `/bbs/:cat`
### Rule 2
- `title`: `最新主题 - 精华区`
- `source`:
  - `bbs.wenxuecity.com/:cat`
- `target`: `/bbs/:cat/1`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/wenxuecity/bbs/tzlc",
  "heat": 4,
  "location": "bbs.ts",
  "maintainers": [
    "changlan"
  ],
  "name": "最新主题",
  "parameters": {
    "cat": "版面名, 可在 URL 中找到",
    "elite": "是否精华区, 1 为精华区"
  },
  "path": "/bbs/:cat/:elite?",
  "radar": [
    {
      "source": [
        "bbs.wenxuecity.com/:cat"
      ],
      "target": "/bbs/:cat"
    },
    {
      "source": [
        "bbs.wenxuecity.com/:cat"
      ],
      "target": "/bbs/:cat/1",
      "title": "最新主题 - 精华区"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "文学城 | 移民论坛（immigration） - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "177651896288583713",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.wenxuecity.com/immigration/?elite=1",
      "title": "文学城 | 移民论坛（immigration）",
      "type": "feed",
      "url": "rsshub://wenxuecity/bbs/immigration/1"
    },
    {
      "description": "文学城 | 我爱我家（myhouse） - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "177651896288583712",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.wenxuecity.com/myhouse/?elite=1",
      "title": "文学城 | 我爱我家（myhouse）",
      "type": "feed",
      "url": "rsshub://wenxuecity/bbs/myhouse/1"
    }
  ]
}
```
