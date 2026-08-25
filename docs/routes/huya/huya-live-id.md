# 虎牙直播 - 直播间开播

## Coverage
`index-only`

## Route
- Namespace: `huya`
- Namespace Name: `虎牙直播`
- Route Path: `/huya/live/:id`
- Route Name: `直播间开播`
- Example: `/huya/live/edmunddzhang`
- URL: `www.huya.com`
- Language: `_None_`
- Categories: `live`
- Maintainers: `SettingDust, xyqfer`
- Source Location: `live.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 直播间id或主播名(有一些id是名字，如上)


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `huya.com/:id`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "example": "/huya/live/edmunddzhang",
  "heat": 0,
  "location": "live.ts",
  "maintainers": [
    "SettingDust",
    "xyqfer"
  ],
  "name": "直播间开播",
  "parameters": {
    "id": "直播间id或主播名(有一些id是名字，如上)"
  },
  "path": "/live/:id",
  "radar": [
    {
      "source": [
        "huya.com/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
