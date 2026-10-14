# 北京社科网 - 基金项目管理平台

## Coverage
`index-only`

## Route
- Namespace: `bjsk`
- Namespace Name: `北京社科网`
- Route Path: `/bjsk/keti/:id?`
- Route Name: `基金项目管理平台`
- Example: `/bjsk/keti`
- URL: `keti.bjsk.org.cn/indexAction!to_index.action`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `keti.ts`
- Source Module: `_None_`

## Description
| 通知公告                         | 资料下载                         |
| -------------------------------- | -------------------------------- |
| 402881027cbb8c6f017cbb8e17710002 | 2c908aee818e04f401818e08645c0002 |

## Parameters
- `id`: 分类 id，见下表，默认为通知公告


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
  - `keti.bjsk.org.cn/indexAction!to_index.action`
  - `keti.bjsk.org.cn/`
- `target`: `/keti`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 通知公告                         | 资料下载                         |\n| -------------------------------- | -------------------------------- |\n| 402881027cbb8c6f017cbb8e17710002 | 2c908aee818e04f401818e08645c0002 |",
  "example": "/bjsk/keti",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "keti.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "基金项目管理平台",
  "parameters": {
    "id": "分类 id，见下表，默认为通知公告"
  },
  "path": "/keti/:id?",
  "radar": [
    {
      "source": [
        "keti.bjsk.org.cn/indexAction!to_index.action",
        "keti.bjsk.org.cn/"
      ],
      "target": "/keti"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "北京社科基金项目管理平台 - 通知公告 - Powered by RSSHub",
      "errorAt": "2026-07-08T02:36:56.334Z",
      "errorMessage": "Failed to fetch\n",
      "id": "116470154564273152",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://keti.bjsk.org.cn/articleAction!to_moreList.action?entity.columnId=402881027cbb8c6f017cbb8e17710002&pagination.pageSize=100",
      "title": "北京社科基金项目管理平台 - 通知公告",
      "type": "feed",
      "url": "rsshub://bjsk/keti"
    }
  ],
  "url": "keti.bjsk.org.cn/indexAction!to_index.action"
}
```
