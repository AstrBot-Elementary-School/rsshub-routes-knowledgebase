# 美拍 - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `meipai`
- Namespace Name: `美拍`
- Route Path: `/meipai/user/:uid`
- Route Name: `用户动态`
- Example: `/meipai/user/56537299`
- URL: `www.meipai.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `ihewro`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 id, 可在分享出去获得的用户主页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.meipai.com/user/:uid`
- `target`: `/user/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/meipai/user/56537299",
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "ihewro"
  ],
  "name": "用户动态",
  "parameters": {
    "uid": "用户 id, 可在分享出去获得的用户主页 URL 中找到"
  },
  "path": "/user/:uid",
  "radar": [
    {
      "source": [
        "www.meipai.com/user/:uid"
      ],
      "target": "/user/:uid"
    }
  ],
  "topFeeds": [],
  "url": "www.meipai.com"
}
```
