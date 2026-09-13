# iCity - iMuseum 城市展览

## Coverage
`index-only`

## Route
- Namespace: `icity`
- Namespace Name: `iCity`
- Route Path: `/icity/imuseum/:city/:type?`
- Route Name: `iMuseum 城市展览`
- Example: `/icity/imuseum/guangzhou/latest`
- URL: `icity.ly`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `chouj`
- Source Location: `imuseum.ts`
- Source Module: `_None_`

## Description
iMuseum（每日环球展览）各城市正在进行与即将开始的展览。城市与类型均取自站点 URL 路径，例如 `guangzhou/latest`。

## Parameters
- `city`: 城市，取自站点 URL 中的城市路径，如 guangzhou、shanghai、beijing
- `type`: {"default": "latest", "description": "展览列表类型", "options": [{"label": "全部", "value": "all"}, {"label": "最新", "value": "latest"}, {"label": "热门", "value": "hot"}, {"label": "即将结束", "value": "end_soon"}, {"label": "即将开始", "value": "coming"}, {"label": "已结束", "value": "outdated"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `art.icity.ly/:city`
- `target`: `/imuseum/:city`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "description": "iMuseum（每日环球展览）各城市正在进行与即将开始的展览。城市与类型均取自站点 URL 路径，例如 `guangzhou/latest`。",
  "example": "/icity/imuseum/guangzhou/latest",
  "heat": 0,
  "location": "imuseum.ts",
  "maintainers": [
    "chouj"
  ],
  "name": "iMuseum 城市展览",
  "parameters": {
    "city": "城市，取自站点 URL 中的城市路径，如 guangzhou、shanghai、beijing",
    "type": {
      "default": "latest",
      "description": "展览列表类型",
      "options": [
        {
          "label": "全部",
          "value": "all"
        },
        {
          "label": "最新",
          "value": "latest"
        },
        {
          "label": "热门",
          "value": "hot"
        },
        {
          "label": "即将结束",
          "value": "end_soon"
        },
        {
          "label": "即将开始",
          "value": "coming"
        },
        {
          "label": "已结束",
          "value": "outdated"
        }
      ]
    }
  },
  "path": "/imuseum/:city/:type?",
  "radar": [
    {
      "source": [
        "art.icity.ly/:city"
      ],
      "target": "/imuseum/:city"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
