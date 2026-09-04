# 鹰角网络 - 明日方舟：终末地 - 游戏公告与新闻

## Coverage
`index-only`

## Route
- Namespace: `hypergryph`
- Namespace Name: `鹰角网络`
- Route Path: `/hypergryph/endfield/news/:group?`
- Route Name: `明日方舟：终末地 - 游戏公告与新闻`
- Example: `/hypergryph/endfield/news`
- URL: `endfield.hypergryph.com/news`
- Language: `_None_`
- Categories: `game`
- Maintainers: `E-larex`
- Source Location: `endfield/news.ts`
- Source Module: `_None_`

## Description
| 全部 | 公告    | 活动   | 新闻 |
| ---- | ------- | ------ | ---- |
| ALL  | notices | events | news |

## Parameters
- `group`: 分组，默认为 `ALL`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `endfield.hypergryph.com/news`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 全部 | 公告    | 活动   | 新闻 |\n| ---- | ------- | ------ | ---- |\n| ALL  | notices | events | news |",
  "example": "/hypergryph/endfield/news",
  "heat": 2,
  "location": "endfield/news.ts",
  "maintainers": [
    "E-larex"
  ],
  "name": "明日方舟：终末地 - 游戏公告与新闻",
  "parameters": {
    "group": "分组，默认为 `ALL`"
  },
  "path": "/endfield/news/:group?",
  "radar": [
    {
      "source": [
        "endfield.hypergryph.com/news"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "《明日方舟：终末地》游戏公告与新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1161356855100702720",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://endfield.hypergryph.com/news",
      "title": "《明日方舟：终末地》游戏公告与新闻",
      "type": "feed",
      "url": "rsshub://hypergryph/endfield/news"
    }
  ],
  "url": "endfield.hypergryph.com/news"
}
```
