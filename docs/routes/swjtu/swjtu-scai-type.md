# 西南交通大学 - 计算机与人工智能学院

## Coverage
`index-only`

## Route
- Namespace: `swjtu`
- Namespace Name: `西南交通大学`
- Route Path: `/swjtu/scai/:type`
- Route Name: `计算机与人工智能学院`
- Example: `/swjtu/scai/bks`
- URL: `www.swjtu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `AzureG03, SuperJeason`
- Source Location: `scai.ts`
- Source Module: `_None_`

## Description
| 分区       | 参数 |
| ---------- | ---- |
| 本科生教育 | bks  |
| 研究生教育 | yjs  |
| 学生工作   | xsgz |

## Parameters
- `type`: 通知类型


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
  - `scai.swjtu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 分区       | 参数 |\n| ---------- | ---- |\n| 本科生教育 | bks  |\n| 研究生教育 | yjs  |\n| 学生工作   | xsgz |",
  "example": "/swjtu/scai/bks",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "scai.ts",
  "maintainers": [
    "AzureG03",
    "SuperJeason"
  ],
  "name": "计算机与人工智能学院",
  "parameters": {
    "type": "通知类型"
  },
  "path": "/scai/:type",
  "radar": [
    {
      "source": [
        "scai.swjtu.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "西南交大计院-本科生教育 - Powered by RSSHub",
      "errorAt": "2026-02-09T08:47:44.183Z",
      "errorMessage": "[GET] \"https://scai.swjtu.edu.cn/web/page-module.html?mid=B730BEB095B31840\": <no response> fetch failed\n",
      "id": "113640637727987712",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://scai.swjtu.edu.cn/web/page-module.html?mid=B730BEB095B31840",
      "title": "西南交大计院-本科生教育",
      "type": "feed",
      "url": "rsshub://swjtu/scai/bks"
    }
  ]
}
```
