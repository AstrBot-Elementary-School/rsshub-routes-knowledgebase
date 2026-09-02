# Chinese Academy of Geological Sciences - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `cags`
- Namespace Name: `Chinese Academy of Geological Sciences`
- Route Path: `/cags/edu/:category`
- Route Name: `研究生院`
- Example: `/cags/edu/tzgg`
- URL: `cags.cgs.gov.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Chikit-L`
- Source Location: `edu/index.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 要闻简讯 | 博士生招生 | 硕士生招生 | 大学生夏令营 |
| -------- | -------- | ---------- | ---------- | ------------ |
| tzgg     | ywjx     | zs\_bss    | zs\_sss    | zs\_dxsxly   |

## Parameters
- `category`: 通知频道，可选 tzgg/ywjx/zs_bss/zs_sss/zs_dxsxly


## Features
- `antiCrawler`: false
- `requireConfig`: false
- `requirePuppeteer`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `edu.cags.ac.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 要闻简讯 | 博士生招生 | 硕士生招生 | 大学生夏令营 |\n| -------- | -------- | ---------- | ---------- | ------------ |\n| tzgg     | ywjx     | zs\\_bss    | zs\\_sss    | zs\\_dxsxly   |",
  "example": "/cags/edu/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "edu/index.ts",
  "maintainers": [
    "Chikit-L"
  ],
  "name": "研究生院",
  "parameters": {
    "category": "通知频道，可选 tzgg/ywjx/zs_bss/zs_sss/zs_dxsxly"
  },
  "path": "/edu/:category",
  "radar": [
    {
      "source": [
        "edu.cags.ac.cn/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "77888993877532672",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://edu.cags.ac.cn/#/dky/list/barId=tzgg/cmsNavCategory=1",
      "title": "通知公告",
      "type": "feed",
      "url": "rsshub://cags/edu/tzgg"
    }
  ]
}
```
