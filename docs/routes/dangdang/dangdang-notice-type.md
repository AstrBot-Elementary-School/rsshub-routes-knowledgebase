# 当当开放平台 - 公告

## Coverage
`index-only`

## Route
- Namespace: `dangdang`
- Namespace Name: `当当开放平台`
- Route Path: `/dangdang/notice/:type?`
- Route Name: `公告`
- Example: `/dangdang/notice/1`
- URL: `open.dangdang.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `353325487`
- Source Location: `notice.ts`
- Source Module: `_None_`

## Description
| 类型     | type |
| -------- | ---- |
| 全部     | 0    |
| 其他     | 1    |
| 规则变更 | 2    |

## Parameters
- `type`: 公告分类，默认为全部


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
    "programming"
  ],
  "description": "| 类型     | type |\n| -------- | ---- |\n| 全部     | 0    |\n| 其他     | 1    |\n| 规则变更 | 2    |",
  "example": "/dangdang/notice/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "notice.ts",
  "maintainers": [
    "353325487"
  ],
  "name": "公告",
  "parameters": {
    "type": "公告分类，默认为全部"
  },
  "path": "/notice/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "当当开放平台 - 全部 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "161775818139698176",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://open.dangdang.com/home/notice/message/1",
      "title": "当当开放平台 - 全部",
      "type": "feed",
      "url": "rsshub://dangdang/notice"
    }
  ]
}
```
