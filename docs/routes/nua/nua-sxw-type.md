# Nanjing University of the Arts 南京艺术学院 - Shuangxing Information

## Coverage
`index-only`

## Route
- Namespace: `nua`
- Namespace Name: `Nanjing University of the Arts 南京艺术学院`
- Route Path: `/nua/sxw/:type`
- Route Name: `Shuangxing Information`
- Example: `/nua/sxw/230`
- URL: `www.nua.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `evnydd0sf`
- Source Location: `sxw.ts`
- Source Module: `_None_`

## Description
| News Type | Parameters |
| --------- | ---------- |
| 校园电视  | 230        |
| 院部动态  | 232        |
| 动感校园  | 233        |
| 招就指南  | 234        |
| 南艺院报  | 236        |

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
  - `sxw.nua.edu.cn/:type/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| News Type | Parameters |\n| --------- | ---------- |\n| 校园电视  | 230        |\n| 院部动态  | 232        |\n| 动感校园  | 233        |\n| 招就指南  | 234        |\n| 南艺院报  | 236        |",
  "example": "/nua/sxw/230",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "sxw.ts",
  "maintainers": [
    "evnydd0sf"
  ],
  "name": "Shuangxing Information",
  "parameters": {
    "type": "News Type"
  },
  "path": "/sxw/:type",
  "radar": [
    {
      "source": [
        "sxw.nua.edu.cn/:type/list.htm"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
