# Nanjing University of the Arts 南京艺术学院 - Official Information

## Coverage
`index-only`

## Route
- Namespace: `nua`
- Namespace Name: `Nanjing University of the Arts 南京艺术学院`
- Route Path: `/nua/index/:type`
- Route Name: `Official Information`
- Example: `/nua/index/346`
- URL: `www.nua.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `evnydd0sf`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| News Type | Parameters |
| --------- | ---------- |
| 公告      | 346        |
| 南艺要闻  | 332        |

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
  - `www.nua.edu.cn/:type/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| News Type | Parameters |\n| --------- | ---------- |\n| 公告      | 346        |\n| 南艺要闻  | 332        |",
  "example": "/nua/index/346",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "evnydd0sf"
  ],
  "name": "Official Information",
  "parameters": {
    "type": "News Type"
  },
  "path": "/index/:type",
  "radar": [
    {
      "source": [
        "www.nua.edu.cn/:type/list.htm"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
