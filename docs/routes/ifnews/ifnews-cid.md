# 国际金融报 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `ifnews`
- Namespace Name: `国际金融报`
- Route Path: `/ifnews/:cid`
- Route Name: `栏目`
- Example: `/ifnews/48`
- URL: `www.ifnews.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `Origami404`
- Source Location: `column.ts`
- Source Module: `_None_`

## Description
`cid`可在对应栏目的 url 后的参数中获取，如`热点快报`的栏目 url 为`http://www.ifnews.com/column.html?cid=48`, `cid`即为`48`.

## Parameters
- `cid`: 栏目 ID


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "`cid`可在对应栏目的 url 后的参数中获取，如`热点快报`的栏目 url 为`http://www.ifnews.com/column.html?cid=48`, `cid`即为`48`.",
  "example": "/ifnews/48",
  "heat": 0,
  "location": "column.ts",
  "maintainers": [
    "Origami404"
  ],
  "name": "栏目",
  "parameters": {
    "cid": "栏目 ID"
  },
  "path": "/:cid",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
