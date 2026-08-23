# 香水时代 - 香评

## Coverage
`index-only`

## Route
- Namespace: `nosetime`
- Namespace Name: `香水时代`
- Route Path: `/nosetime/:id/:type/:sort?`
- Route Name: `香评`
- Example: `/nosetime/59247733/discuss/new`
- URL: `www.nosetime.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `kt286`
- Source Location: `comment.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 用户id，可在用户主页 URL 中找到
- `type`: 类型，short 一句话香评  discuss 香评
- `sort`: 排序， new 最新  agree 最有用


## Features
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/nosetime/59247733/discuss/new",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "comment.ts",
  "maintainers": [
    "kt286"
  ],
  "name": "香评",
  "parameters": {
    "id": "用户id，可在用户主页 URL 中找到",
    "sort": "排序， new 最新  agree 最有用",
    "type": "类型，short 一句话香评  discuss 香评"
  },
  "path": "/:id/:type/:sort?",
  "topFeeds": []
}
```
