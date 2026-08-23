# Last.fm - 站内 Top 榜单

## Coverage
`index-only`

## Route
- Namespace: `last.fm`
- Namespace Name: `Last.fm`
- Route Path: `/last.fm/top/:country?`
- Route Name: `站内 Top 榜单`
- Example: `/last.fm/top/spain`
- URL: `www.last.fm`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `hoilc`
- Source Location: `top.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `country`: 国家或地区, 需要符合`ISO 3166-1`的英文全称, 可参考`https://zh.wikipedia.org/wiki/ISO_3166-1二位字母代码#正式分配代码`


## Features
- `requireConfig`: [{"description": "Last.fm API key", "name": "LASTFM_API_KEY", "optional": false}]

## Radar
### Rule 1
- `source`:
  - `www.last.fm/charts`
- `target`: `/top`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/last.fm/top/spain",
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
  "location": "top.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "站内 Top 榜单",
  "parameters": {
    "country": "国家或地区, 需要符合`ISO 3166-1`的英文全称, 可参考`https://zh.wikipedia.org/wiki/ISO_3166-1二位字母代码#正式分配代码`"
  },
  "path": "/top/:country?",
  "radar": [
    {
      "source": [
        "www.last.fm/charts"
      ],
      "target": "/top"
    }
  ],
  "topFeeds": []
}
```
