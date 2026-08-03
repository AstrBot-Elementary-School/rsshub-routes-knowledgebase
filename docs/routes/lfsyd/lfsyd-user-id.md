# 旅法师营地 - 用户的帖子

## Coverage
`index-only`

## Route
- Namespace: `lfsyd`
- Namespace Name: `旅法师营地`
- Route Path: `/lfsyd/user/:id?`
- Route Name: `用户的帖子`
- Example: `/lfsyd/user/55547`
- URL: `www.iyingdi.com/`
- Language: `_None_`
- Categories: `game`
- Maintainers: `auto-bot-ty`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
可以在用户主页的 URL 中找到

Example：`https://www.iyingdi.com/tz/people/55547` ，id 是 `55547`

## Parameters
- `id`: 用户 id


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.iyingdi.com/tz/people/:id`
  - `www.iyingdi.com/tz/people/:id/*`
- `target`: `/user/:id`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "可以在用户主页的 URL 中找到\n\nExample：`https://www.iyingdi.com/tz/people/55547` ，id 是 `55547`",
  "example": "/lfsyd/user/55547",
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "auto-bot-ty"
  ],
  "name": "用户的帖子",
  "parameters": {
    "id": "用户 id"
  },
  "path": "/user/:id?",
  "radar": [
    {
      "source": [
        "www.iyingdi.com/tz/people/:id",
        "www.iyingdi.com/tz/people/:id/*"
      ],
      "target": "/user/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "www.iyingdi.com/"
}
```
