# AcFun - 用户文章

## Coverage
`index-only`

## Route
- Namespace: `acfun`
- Namespace Name: `AcFun`
- Route Path: `/acfun/user/article/:uid`
- Route Name: `用户文章`
- Example: `/acfun/user/article/1384329`
- URL: `www.acfun.cn`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `tiaod`
- Source Location: `user-article.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 UID


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.acfun.cn/u/:id`
- `target`: `/user/article/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/acfun/user/article/1384329",
  "heat": 0,
  "location": "user-article.ts",
  "maintainers": [
    "tiaod"
  ],
  "name": "用户文章",
  "parameters": {
    "uid": "用户 UID"
  },
  "path": "/user/article/:uid",
  "radar": [
    {
      "source": [
        "www.acfun.cn/u/:id"
      ],
      "target": "/user/article/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "view": 0
}
```
