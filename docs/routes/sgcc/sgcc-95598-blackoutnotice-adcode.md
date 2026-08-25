# 国家电网 - 停电通知

## Coverage
`index-only`

## Route
- Namespace: `sgcc`
- Namespace Name: `国家电网`
- Route Path: `/sgcc/95598/blackoutNotice/:adcode`
- Route Name: `停电通知`
- Example: `/sgcc/95598/blackoutNotice/320100`
- URL: `www.95598.cn/osgweb/blackoutNotice`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `ocleo1`
- Source Location: `blackout-notice.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `adcode`: 地区代码，可通过 `/sgcc/95598/helper` 查询


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.95598.cn/osgweb/blackoutNotice`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/sgcc/95598/blackoutNotice/320100",
  "heat": 0,
  "location": "blackout-notice.ts",
  "maintainers": [
    "ocleo1"
  ],
  "name": "停电通知",
  "parameters": {
    "adcode": "地区代码，可通过 `/sgcc/95598/helper` 查询"
  },
  "path": "/95598/blackoutNotice/:adcode",
  "radar": [
    {
      "source": [
        "www.95598.cn/osgweb/blackoutNotice"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.95598.cn/osgweb/blackoutNotice"
}
```
