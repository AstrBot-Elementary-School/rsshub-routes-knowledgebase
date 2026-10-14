# Nanjing University of the Arts 南京艺术学院 - Graduate Institute

## Coverage
`index-only`

## Route
- Namespace: `nua`
- Namespace Name: `Nanjing University of the Arts 南京艺术学院`
- Route Path: `/nua/gra/:type`
- Route Name: `Graduate Institute`
- Example: `/nua/gra/1959`
- URL: `www.nua.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `evnydd0sf`
- Source Location: `gra.ts`
- Source Module: `_None_`

## Description
| News Type | Parameters |
| --------- | ---------- |
| 招生工作  | 1959       |
| 培养工作  | 1962       |
| 学位工作  | 1958       |

## Parameters
- `type`: News Type


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `grad.nua.edu.cn/:type/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| News Type | Parameters |\n| --------- | ---------- |\n| 招生工作  | 1959       |\n| 培养工作  | 1962       |\n| 学位工作  | 1958       |",
  "example": "/nua/gra/1959",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "gra.ts",
  "maintainers": [
    "evnydd0sf"
  ],
  "name": "Graduate Institute",
  "parameters": {
    "type": "News Type"
  },
  "path": "/gra/:type",
  "radar": [
    {
      "source": [
        "grad.nua.edu.cn/:type/list.htm"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
