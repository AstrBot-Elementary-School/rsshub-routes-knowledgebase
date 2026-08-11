# 中国科学技术大学 - 官网通知公告

## Coverage
`index-only`

## Route
- Namespace: `ustc`
- Namespace Name: `中国科学技术大学`
- Route Path: `/ustc/news/:type?`
- Route Name: `官网通知公告`
- Example: `/ustc/news/gl`
- URL: `ustc.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `hang333, jasongzy`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 教学类 | 科研类 | 管理类 | 服务类 |
| ------ | ------ | ------ | ------ |
| jx     | ky     | gl     | fw     |

## Parameters
- `type`: 分类，默认为管理类


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
  - `ustc.edu.cn/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 教学类 | 科研类 | 管理类 | 服务类 |\n| ------ | ------ | ------ | ------ |\n| jx     | ky     | gl     | fw     |",
  "example": "/ustc/news/gl",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "index.ts",
  "maintainers": [
    "hang333",
    "jasongzy"
  ],
  "name": "官网通知公告",
  "parameters": {
    "type": "分类，默认为管理类"
  },
  "path": "/news/:type?",
  "radar": [
    {
      "source": [
        "ustc.edu.cn/"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "中国科学技术大学 - 管理类通知 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "78281600264570880",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ustc.edu.cn/tzgg/glltz.htm",
      "title": "中国科学技术大学 - 管理类通知",
      "type": "feed",
      "url": "rsshub://ustc/news/gl"
    },
    {
      "description": "中国科学技术大学 - 管理类通知 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "134914934896593920",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ustc.edu.cn/tzgg/glltz.htm",
      "title": "中国科学技术大学 - 管理类通知",
      "type": "feed",
      "url": "rsshub://ustc/news"
    }
  ],
  "url": "ustc.edu.cn/"
}
```
