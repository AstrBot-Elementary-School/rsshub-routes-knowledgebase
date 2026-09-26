# 语雀 - 知识库

## Coverage
`index-only`

## Route
- Namespace: `yuque`
- Namespace Name: `语雀`
- Route Path: `/yuque/:name/:book`
- Route Name: `知识库`
- Example: `/yuque/ruanyf/weekly`
- URL: `yuque.com`
- Language: `_None_`
- Categories: `study`
- Maintainers: `aha2mao, ltaoo`
- Source Location: `book.ts`
- Source Module: `_None_`

## Description
| Node.js 专栏                                             | 阮一峰每周分享                                                 | 语雀使用手册                                             |
| -------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------- |
| [/yuque/egg/nodejs](https://rsshub.app/yuque/egg/nodejs) | [/yuque/ruanyf/weekly](https://rsshub.app/yuque/ruanyf/weekly) | [/yuque/yuque/help](https://rsshub.app/yuque/yuque/help) |

## Parameters
- `name`: 用戶名
- `book`: 知识库 ID


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
  - `yuque.com/:name/:book`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "| Node.js 专栏                                             | 阮一峰每周分享                                                 | 语雀使用手册                                             |\n| -------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------- |\n| [/yuque/egg/nodejs](https://rsshub.app/yuque/egg/nodejs) | [/yuque/ruanyf/weekly](https://rsshub.app/yuque/ruanyf/weekly) | [/yuque/yuque/help](https://rsshub.app/yuque/yuque/help) |",
  "example": "/yuque/ruanyf/weekly",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 370,
  "location": "book.ts",
  "maintainers": [
    "aha2mao",
    "ltaoo"
  ],
  "name": "知识库",
  "parameters": {
    "book": "知识库 ID",
    "name": "用戶名"
  },
  "path": "/:name/:book",
  "radar": [
    {
      "source": [
        "yuque.com/:name/:book"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "👩‍💻🥷渗透 / 安全攻防🥷👩‍💻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57371095438208000",
      "image": "https://cdn.nlark.com/yuque/0/2020/jpeg/anonymous/1592796105285-8085e728-e5fc-4669-9b4e-deb5c0b07f77.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://www.yuque.com/jianouzuihuai/attack-defense",
      "title": "👩‍💻🥷渗透 / 安全攻防🥷👩‍💻",
      "type": "feed",
      "url": "rsshub://yuque/jianouzuihuai/attack-defense"
    },
    {
      "description": "看大厂如何用AI做设计 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63457324457775104",
      "image": "https://cdn.nlark.com/yuque/0/2020/png/275935/1609243978082-avatar/c4211b8d-79b9-44ff-830d-0ad503ed69c4.png",
      "ownerUserId": null,
      "siteUrl": "https://www.yuque.com/wikidesign/vngzgk",
      "title": "大厂AI实践",
      "type": "feed",
      "url": "rsshub://yuque/wikidesign/vngzgk"
    }
  ]
}
```
