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
_None_

## Parameters
- `user`: Last.fm 用户名


## Features
- `requireConfig`: [{"description": "Last.fm API key", "name": "LASTFM_API_KEY", "optional": false}]

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
  "example": "/last.fm/recent/yeFoenix",
  "features": {
    "requireConfig": [
      {
        "description": "Last.fm API key",
        "name": "LASTFM_API_KEY",
        "optional": false
      }
    ]
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
