# 南开大学 - 研究生招生网

## Coverage
`index-only`

## Route
- Namespace: `nankai`
- Namespace Name: `南开大学`
- Route Path: `/nankai/yzb/:type?`
- Route Name: `研究生招生网`
- Example: `/nankai/yzb/5509`
- URL: `yzb.nankai.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `sddzhyc`
- Source Location: `yzb.ts`
- Source Module: `_None_`

## Description
| 硕士招生 | 博士招生 | 港澳台研究生最新信息 |
| -------- | -------- | -------------------- |
| 5509     | 2552     | 2562                 |

## Parameters
- `type`: 栏目名（若为空则默认为“硕士招生”）


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `yzb.nankai.edu.cn`
  - `yzb.nankai.edu.cn/:type/list.htm`
- `target`: `/yzb/:type?`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 硕士招生 | 博士招生 | 港澳台研究生最新信息 |\n| -------- | -------- | -------------------- |\n| 5509     | 2552     | 2562                 |",
  "example": "/nankai/yzb/5509",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "yzb.ts",
  "maintainers": [
    "sddzhyc"
  ],
  "name": "研究生招生网",
  "parameters": {
    "type": "栏目名（若为空则默认为“硕士招生”）"
  },
  "path": "/yzb/:type?",
  "radar": [
    {
      "source": [
        "yzb.nankai.edu.cn",
        "yzb.nankai.edu.cn/:type/list.htm"
      ],
      "target": "/yzb/:type?"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "南开大学研究生招生网-硕士招生 - Powered by RSSHub",
      "errorAt": "2026-09-03T03:17:27.226Z",
      "errorMessage": "Failed to fetch\n[GET] \"https://yzb.nankai.edu.cn/5509/list.htm\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 222.30.45.190:443, 2001:250:401:d450::190:443, timeout: 10000ms))\n",
      "id": "167782987907531776",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://yzb.nankai.edu.cn/5509/list.htm",
      "title": "南开大学研究生招生网-硕士招生",
      "type": "feed",
      "url": "rsshub://nankai/yzb/5509"
    }
  ],
  "url": "yzb.nankai.edu.cn"
}
```
