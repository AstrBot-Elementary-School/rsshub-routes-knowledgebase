# 快科技 - 排行

## Coverage
`index-only`

## Route
- Namespace: `mydrivers`
- Namespace Name: `快科技`
- Route Path: `/mydrivers/rank/:range?`
- Route Name: `排行`
- Example: `/mydrivers/rank`
- URL: `m.mydrivers.com/newsclass.aspx`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `rank.ts`
- Source Module: `_None_`

## Description
| 24 小时最热 | 本周最热 | 本月最热 |
| ----------- | -------- | -------- |
| 0           | 1        | 2        |

## Parameters
- `range`: 时间范围，见下表，默认为24小时最热


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
  - `m.mydrivers.com/newsclass.aspx`
- `target`: `/rank`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 24 小时最热 | 本周最热 | 本月最热 |\n| ----------- | -------- | -------- |\n| 0           | 1        | 2        |",
  "example": "/mydrivers/rank",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 38,
  "location": "rank.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "排行",
  "parameters": {
    "range": "时间范围，见下表，默认为24小时最热"
  },
  "path": "/rank/:range?",
  "radar": [
    {
      "source": [
        "m.mydrivers.com/newsclass.aspx"
      ],
      "target": "/rank"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "手机驱动之家是驱动之家的手机门户网站，为亿万用户打造一个手机联通世界的超级平台，提供24小时全面及时的中文IT资讯。手机驱动之家触屏版 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66732747558908928",
      "image": "https://11.mydrivers.com/m/images/v1/kkj_hearlogo.png",
      "ownerUserId": null,
      "siteUrl": "https://m.mydrivers.com/newsclass.aspx?tid=1001",
      "title": "快科技 - 24小时最热",
      "type": "feed",
      "url": "rsshub://mydrivers/rank"
    },
    {
      "description": "手机驱动之家是驱动之家的手机门户网站，为亿万用户打造一个手机联通世界的超级平台，提供24小时全面及时的中文IT资讯。手机驱动之家触屏版 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "122531537836972032",
      "image": "https://11.mydrivers.com/m/images/v1/kkj_hearlogo.png",
      "ownerUserId": null,
      "siteUrl": "https://m.mydrivers.com/newsclass.aspx?tid=1001",
      "title": "快科技 - 24小时最热",
      "type": "feed",
      "url": "rsshub://mydrivers/rank/0"
    }
  ],
  "url": "m.mydrivers.com/newsclass.aspx"
}
```
