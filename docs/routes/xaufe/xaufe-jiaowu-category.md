# 西安财经大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `xaufe`
- Namespace Name: `西安财经大学`
- Route Path: `/xaufe/jiaowu/:category?`
- Route Name: `教务处`
- Example: `/xaufe/jiaowu/tzgg`
- URL: `jiaowu.xaufe.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `shaokeyibb`
- Source Location: `jiaowu.ts`
- Source Module: `_None_`

## Description
| 通知公告 |
| :------: |
|   tzgg   |

## Parameters
- `category`: 分类，默认为通知公告


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 |\n| :------: |\n|   tzgg   |",
  "example": "/xaufe/jiaowu/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "jiaowu.ts",
  "maintainers": [
    "shaokeyibb"
  ],
  "name": "教务处",
  "parameters": {
    "category": "分类，默认为通知公告"
  },
  "path": "/jiaowu/:category?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "通知公告-西安财经大学 教务处（招生办公室） - Powered by RSSHub",
      "errorAt": "2025-06-03T15:17:09.543Z",
      "errorMessage": "[GET] \"http://jiaowu.xaufe.edu.cn/index/tzgg.htm\": <no response> fetch failed (other side closed)\n",
      "id": "88758023569371137",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://jiaowu.xaufe.edu.cn/index/tzgg.htm",
      "title": "通知公告-西安财经大学 教务处（招生办公室）",
      "type": "feed",
      "url": "rsshub://xaufe/jiaowu/tzgg"
    }
  ]
}
```
