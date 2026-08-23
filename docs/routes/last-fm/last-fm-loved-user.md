# Last.fm - 用户 Love 记录

## Coverage
`index-only`

## Route
- Namespace: `last.fm`
- Namespace Name: `Last.fm`
- Route Path: `/last.fm/loved/:user`
- Route Name: `用户 Love 记录`
- Example: `/last.fm/loved/yeFoenix`
- URL: `www.last.fm`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `hoilc`
- Source Location: `loved.ts`
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
  "example": "/last.fm/loved/yeFoenix",
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
  "location": "loved.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "用户 Love 记录",
  "parameters": {
    "user": "Last.fm 用户名"
  },
  "path": "/loved/:user",
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
