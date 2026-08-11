# 东北大学 - 研究生招生信息网

## Coverage
`index-only`

## Route
- Namespace: `neu`
- Namespace Name: `东北大学`
- Route Path: `/neu/yz/:type`
- Route Name: `研究生招生信息网`
- Example: `/neu/yz/master1`
- URL: `yz.neu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `paintstar`
- Source Location: `yz.ts`
- Source Module: `_None_`

## Description
| 分类名   | 分类 id  |
| -------- | -------- |
| 硕士公告 | master1  |
| 硕士简章 | master2  |
| 博士公告 | phd1     |
| 博士简章 | phd2     |
| 下载中心 | download |

## Parameters
- `type`: 分类id,见下表


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
  - `yz.neu.edu.cn/:type/list.htm`
- `target`: `/yz/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 分类名   | 分类 id  |\n| -------- | -------- |\n| 硕士公告 | master1  |\n| 硕士简章 | master2  |\n| 博士公告 | phd1     |\n| 博士简章 | phd2     |\n| 下载中心 | download |",
  "example": "/neu/yz/master1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "yz.ts",
  "maintainers": [
    "paintstar"
  ],
  "name": "研究生招生信息网",
  "parameters": {
    "type": "分类id,见下表"
  },
  "path": "/yz/:type",
  "radar": [
    {
      "source": [
        "yz.neu.edu.cn/:type/list.htm"
      ],
      "target": "/yz/:type"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "博士公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "177286517780633600",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://yz.neu.edu.cn/",
      "title": "博士公告-东北大学研究生招生信息网",
      "type": "feed",
      "url": "rsshub://neu/yz/phd1"
    },
    {
      "description": "博士简章 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "177286544922054656",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://yz.neu.edu.cn/",
      "title": "博士简章-东北大学研究生招生信息网",
      "type": "feed",
      "url": "rsshub://neu/yz/phd2"
    }
  ],
  "url": "yz.neu.edu.cn"
}
```
