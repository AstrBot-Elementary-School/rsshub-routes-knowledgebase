# 丁香园 - 板块

## Coverage
`index-only`

## Route
- Namespace: `dxy`
- Namespace Name: `丁香园`
- Route Path: `/dxy/bbs/board/:boardId`
- Route Name: `板块`
- Example: `/dxy/bbs/board/46`
- URL: `dxy.cn`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `board.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `specialId`: 板块 ID，可在对应板块页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.dxy.cn/bbs/newweb/pc/category/:boardIdId`
- `target`: `/bbs/board/:boardIdId`
### Rule 2
- `source`:
  - `3g.dxy.cn/bbs/board/:boardIdId`
- `target`: `/bbs/board/:boardIdId`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/dxy/bbs/board/46",
  "heat": 11,
  "location": "board.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "板块",
  "parameters": {
    "specialId": "板块 ID，可在对应板块页 URL 中找到"
  },
  "path": "/bbs/board/:boardId",
  "radar": [
    {
      "source": [
        "www.dxy.cn/bbs/newweb/pc/category/:boardIdId"
      ],
      "target": "/bbs/board/:boardIdId"
    },
    {
      "source": [
        "3g.dxy.cn/bbs/board/:boardIdId"
      ],
      "target": "/bbs/board/:boardIdId"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "824472 內容 1692847 关注 - Powered by RSSHub",
      "errorAt": "2025-04-19T04:12:04.568Z",
      "errorMessage": "请求方法不存在\n",
      "id": "72885777699624960",
      "image": "https://img1.dxycdn.com/2022/0119/688/9942937579838937253-73.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://www.dxy.cn/bbs/newweb/pc/category/46",
      "title": "神经内外",
      "type": "feed",
      "url": "rsshub://dxy/bbs/board/46"
    },
    {
      "description": "1860010 內容 565867 关注 - Powered by RSSHub",
      "errorAt": "2025-04-21T10:13:01.990Z",
      "errorMessage": "Failed to fetch\n",
      "id": "74667712210835456",
      "image": "https://img1.dxycdn.com/2021/1203/370/5833322026967668153-13.png",
      "ownerUserId": null,
      "siteUrl": "https://www.dxy.cn/bbs/newweb/pc/category/50",
      "title": "骨科",
      "type": "feed",
      "url": "rsshub://dxy/bbs/board/50"
    }
  ]
}
```
