# 中国计算机学会 - 大数据专家委员会

## Coverage
`index-only`

## Route
- Namespace: `ccf`
- Namespace Name: `中国计算机学会`
- Route Path: `/ccf/tfbd/:caty/:id`
- Route Name: `大数据专家委员会`
- Example: `/ccf/tfbd/xwdt/tzgg`
- URL: `ccf.org.cn`
- Language: `_None_`
- Categories: `study`
- Maintainers: `tudou027`
- Source Location: `tfbd/index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `caty`: 主分类，可在 URL 找到
- `id`: 子分类，可在 URL 找到


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
  - `tfbd.ccf.org.cn/tfbd/:caty/:id`
### Rule 2
- `source`:
  - `tfbd.ccf.org.cn/`
- `target`: `/tfbd/xwdt/tzgg`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/ccf/tfbd/xwdt/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 11,
  "location": "tfbd/index.ts",
  "maintainers": [
    "tudou027"
  ],
  "name": "大数据专家委员会",
  "parameters": {
    "caty": "主分类，可在 URL 找到",
    "id": "子分类，可在 URL 找到"
  },
  "path": "/tfbd/:caty/:id",
  "radar": [
    {
      "source": [
        "tfbd.ccf.org.cn/tfbd/:caty/:id"
      ]
    },
    {
      "source": [
        "tfbd.ccf.org.cn/"
      ],
      "target": "/tfbd/xwdt/tzgg"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "大数据专家委员会 - 通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63782767516912640",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://tfbd.ccf.org.cn/tfbd/xwdt/tzgg/",
      "title": "大数据专家委员会 - 通知公告",
      "type": "feed",
      "url": "rsshub://ccf/tfbd/xwdt/tzgg"
    }
  ]
}
```
