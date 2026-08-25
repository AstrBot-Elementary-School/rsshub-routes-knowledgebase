# 755 - 用户时间线

## Coverage
`index-only`

## Route
- Namespace: `7gogo`
- Namespace Name: `755`
- Route Path: `/7gogo/user/:username`
- Route Name: `用户时间线`
- Example: `/7gogo/user/akimoto-manatsu`
- URL: `7gogo.jp`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `hoilc`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: 用户名, 可在 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `7gogo.jp/:username`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/7gogo/user/akimoto-manatsu",
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "用户时间线",
  "parameters": {
    "username": "用户名, 可在 URL 中找到"
  },
  "path": "/user/:username",
  "radar": [
    {
      "source": [
        "7gogo.jp/:username"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
