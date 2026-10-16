# Last.fm - 用户播放记录

## Coverage
`index-only`

## Route
- Namespace: `last.fm`
- Namespace Name: `Last.fm`
- Route Path: `/last.fm/recent/:user`
- Route Name: `用户播放记录`
- Example: `/last.fm/recent/yeFoenix`
- URL: `www.last.fm`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `hoilc`
- Source Location: `recent.ts`
- Source Module: `_None_`

## Description
未配置 LASTFM\_API\_KEY 时使用公开页面，公开页面的时间精度为分钟。

## Parameters
- `user`: Last.fm 用户名


## Features
- `requirePuppeteer`: true
- `requireConfig`: [{"description": "Last.fm API key", "name": "LASTFM_API_KEY", "optional": true}]

## Radar
### Rule 1
- `source`:
  - `www.last.fm/user/:user`
  - `www.last.fm/user/:user/*`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "未配置 LASTFM\\_API\\_KEY 时使用公开页面，公开页面的时间精度为分钟。",
  "example": "/last.fm/recent/yeFoenix",
  "features": {
    "requireConfig": [
      {
        "description": "Last.fm API key",
        "name": "LASTFM_API_KEY",
        "optional": true
      }
    ],
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "recent.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "用户播放记录",
  "parameters": {
    "user": "Last.fm 用户名"
  },
  "path": "/recent/:user",
  "radar": [
    {
      "source": [
        "www.last.fm/user/:user",
        "www.last.fm/user/:user/*"
      ]
    }
  ],
  "topFeeds": []
}
```
