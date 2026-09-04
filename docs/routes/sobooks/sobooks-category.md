# SoBooks - 首页

## Coverage
`index-only`

## Route
- Namespace: `sobooks`
- Namespace Name: `SoBooks`
- Route Path: `/sobooks/:category?`
- Route Name: `首页`
- Example: `/sobooks`
- URL: `sobooks.net`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 分类     | 分类名           |
| -------- | ---------------- |
| 小说文学 | xiaoshuowenxue   |
| 历史传记 | lishizhuanji     |
| 人文社科 | renwensheke      |
| 励志成功 | lizhichenggong   |
| 经济管理 | jingjiguanli     |
| 学习教育 | xuexijiaoyu      |
| 生活时尚 | shenghuoshishang |
| 英文原版 | yingwenyuanban   |

## Parameters
- `category`: 分类, 见下表


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
  - `sobooks.net/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "| 分类     | 分类名           |\n| -------- | ---------------- |\n| 小说文学 | xiaoshuowenxue   |\n| 历史传记 | lishizhuanji     |\n| 人文社科 | renwensheke      |\n| 励志成功 | lizhichenggong   |\n| 经济管理 | jingjiguanli     |\n| 学习教育 | xuexijiaoyu      |\n| 生活时尚 | shenghuoshishang |\n| 英文原版 | yingwenyuanban   |",
  "example": "/sobooks",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 20,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "首页",
  "parameters": {
    "category": "分类, 见下表"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "sobooks.net/:category"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-06-25T00:45:21.760Z",
      "errorMessage": "[GET] \"https://www.sobooks.net/\": <no response> fetch failed (self-signed certificate; if the root CA is installed locally, try running Node.js with --use-system-ca)\n",
      "id": "160497068790603856",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://sobooks"
    }
  ]
}
```
