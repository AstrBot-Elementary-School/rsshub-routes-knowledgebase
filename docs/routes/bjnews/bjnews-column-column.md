# 新京报 - 分类

## Coverage
`index-only`

## Route
- Namespace: `bjnews`
- Namespace Name: `新京报`
- Route Path: `/bjnews/column/:column`
- Route Name: `分类`
- Example: `/bjnews/column/204`
- URL: `www.bjnews.com.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `dzx-dzx`
- Source Location: `column.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `column`: 栏目ID, 可从手机版网页URL中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `m.bjnews.com.cn/column/:column.htm`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/bjnews/column/204",
  "features": {},
  "heat": 9,
  "location": "column.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "name": "分类",
  "parameters": {
    "column": "栏目ID, 可从手机版网页URL中找到"
  },
  "path": "/column/:column",
  "radar": [
    {
      "source": [
        "m.bjnews.com.cn/column/:column.htm"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "新京报 - 栏目 - 剥洋葱 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "163162956168540160",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.bjnews.com.cn/column/308.html",
      "title": "新京报 - 栏目 - 剥洋葱",
      "type": "feed",
      "url": "rsshub://bjnews/column/308"
    },
    {
      "description": "新京报 - 栏目 - 新京报小记者 - Powered by RSSHub",
      "errorAt": "2026-03-12T11:23:11.739Z",
      "errorMessage": "[GET] \"https://www.bjnews.com.cn/detail/1771568544129378.html\": 405 Not Allowed\n",
      "id": "163162511365115904",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.bjnews.com.cn/column/9328.html",
      "title": "新京报 - 栏目 - 新京报小记者",
      "type": "feed",
      "url": "rsshub://bjnews/column/9328"
    }
  ],
  "url": "www.bjnews.com.cn"
}
```
