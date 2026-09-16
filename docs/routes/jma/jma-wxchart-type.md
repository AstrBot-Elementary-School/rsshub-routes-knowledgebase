# 気象庁 Japan Meteorological Agency - 天気図

## Coverage
`index-only`

## Route
- Namespace: `jma`
- Namespace Name: `気象庁 Japan Meteorological Agency`
- Route Path: `/jma/wxchart/:type?`
- Route Name: `天気図`
- Example: `/jma/wxchart/daily`
- URL: `www.jma.go.jp/bosai/weather_map/`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `TonyRL`
- Source Location: `wxchart.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"default": "daily", "description": "Chart type", "options": [{"label": "天気図（最新）", "value": "daily"}, {"label": "過去の実況天気図（今月）", "value": "monthly"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.jma.go.jp/bosai/weather_map/`
- `target`: `/wxchart/daily`
### Rule 2
- `source`:
  - `www.data.jma.go.jp/yoho/wxchart/quickmonthly.html`
- `target`: `/wxchart/monthly`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/jma/wxchart/daily",
  "heat": 0,
  "location": "wxchart.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "天気図",
  "parameters": {
    "type": {
      "default": "daily",
      "description": "Chart type",
      "options": [
        {
          "label": "天気図（最新）",
          "value": "daily"
        },
        {
          "label": "過去の実況天気図（今月）",
          "value": "monthly"
        }
      ]
    }
  },
  "path": "/wxchart/:type?",
  "radar": [
    {
      "source": [
        "www.jma.go.jp/bosai/weather_map/"
      ],
      "target": "/wxchart/daily"
    },
    {
      "source": [
        "www.data.jma.go.jp/yoho/wxchart/quickmonthly.html"
      ],
      "target": "/wxchart/monthly"
    }
  ],
  "topFeeds": [],
  "url": "www.jma.go.jp/bosai/weather_map/",
  "view": 2
}
```
