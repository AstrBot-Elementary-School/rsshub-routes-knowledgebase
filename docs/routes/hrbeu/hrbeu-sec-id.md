# 哈尔滨工程大学 - 船舶工程学院

## Coverage
`index-only`

## Route
- Namespace: `hrbeu`
- Namespace Name: `哈尔滨工程大学`
- Route Path: `/hrbeu/sec/:id`
- Route Name: `船舶工程学院`
- Example: `/hrbeu/sec/xshd`
- URL: `yjsy.hrbeu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Chi-hong22`
- Source Location: `sec/list.ts`
- Source Module: `_None_`

## Description
| 学院要闻 | 学术活动 | 通知公告 | 学科方向 |
| :------: | :------: | :------: | :------: |
|   xyyw   |   xshd   |    229   |   xkfx   |

## Parameters
- `id`: 栏目编号，由 `URL` 中获取。


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
  - `sec.hrbeu.edu.cn/:id/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学院要闻 | 学术活动 | 通知公告 | 学科方向 |\n| :------: | :------: | :------: | :------: |\n|   xyyw   |   xshd   |    229   |   xkfx   |",
  "example": "/hrbeu/sec/xshd",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "sec/list.ts",
  "maintainers": [
    "Chi-hong22"
  ],
  "name": "船舶工程学院",
  "parameters": {
    "id": "栏目编号，由 `URL` 中获取。"
  },
  "path": "/sec/:id",
  "radar": [
    {
      "source": [
        "sec.hrbeu.edu.cn/:id/list.htm"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "船舶工程学院 - 通知公告 - Powered by RSSHub",
      "errorAt": "2025-12-03T08:07:25.809Z",
      "errorMessage": "[GET] \"http://sec.hrbeu.edu.cn/229/list.htm\": <no response> fetch failed\n",
      "id": "79438470454595584",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://sec.hrbeu.edu.cn/229/list.htm",
      "title": "船舶工程学院 - 通知公告",
      "type": "feed",
      "url": "rsshub://hrbeu/sec/229"
    }
  ]
}
```
