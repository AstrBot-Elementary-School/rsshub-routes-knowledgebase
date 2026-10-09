# 草榴社区 - 用户主题

## Coverage
`index-only`

## Route
- Namespace: `t66y`
- Namespace Name: `草榴社区`
- Route Path: `/t66y/user/:username`
- Route Name: `用户主题`
- Example: `/t66y/user/金小妹`
- URL: `t66y.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `DIYgod`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: 用户名，与源站 /@用户名 页面一致


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `t66y.com/@:username`
  - `www.t66y.com/@:username`
- `target`: `/user/:username`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/t66y/user/金小妹",
  "features": {
    "nsfw": true
  },
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "用户主题",
  "parameters": {
    "username": "用户名，与源站 /@用户名 页面一致"
  },
  "path": "/user/:username",
  "radar": [
    {
      "source": [
        "t66y.com/@:username",
        "www.t66y.com/@:username"
      ],
      "target": "/user/:username"
    }
  ],
  "topFeeds": []
}
```
