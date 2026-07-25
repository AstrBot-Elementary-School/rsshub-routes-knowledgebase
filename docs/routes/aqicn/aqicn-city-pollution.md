# 空气质量 - 实时 AQI

## Coverage
`index-only`

## Route
- Namespace: `aqicn`
- Namespace Name: `空气质量`
- Route Path: `/aqicn/:city/:pollution?`
- Route Name: `实时 AQI`
- Example: `/aqicn/beijing/pm25`
- URL: `aqicn.org`
- Language: `_None_`
- Categories: `other`
- Maintainers: `ladeng07`
- Source Location: `aqi.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `city`: 城市拼音或地区 ID，详见[aqicn.org](http://aqicn.org/city/)
- `pollution`: 可选择显示更详细的空气污染成分


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `aqicn.org`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/aqicn/beijing/pm25",
  "heat": 13,
  "location": "aqi.ts",
  "maintainers": [
    "ladeng07"
  ],
  "name": "实时 AQI",
  "parameters": {
    "city": "城市拼音或地区 ID，详见[aqicn.org](http://aqicn.org/city/)",
    "pollution": "可选择显示更详细的空气污染成分"
  },
  "path": "/:city/:pollution?",
  "radar": [
    {
      "source": [
        "aqicn.org"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "上海AQI-aqicn.org - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65930115678939136",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://aqicn.org/city/shanghai",
      "title": "上海AQI",
      "type": "feed",
      "url": "rsshub://aqicn/shanghai/pm25,pm10"
    },
    {
      "description": "北京AQI-aqicn.org - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62187667735435264",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://aqicn.org/city/beijing",
      "title": "北京AQI",
      "type": "feed",
      "url": "rsshub://aqicn/beijing/pm25,pm10"
    }
  ],
  "url": "aqicn.org"
}
```
