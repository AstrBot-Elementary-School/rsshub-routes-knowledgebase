# 牛客网 - 热榜

## Coverage
`index-only`

## Route
- Namespace: `nowcoder`
- Namespace Name: `牛客网`
- Route Path: `/nowcoder/hots/:type?`
- Route Name: `热榜`
- Example: `/nowcoder/hots/1?limit=20`
- URL: `nowcoder.com/`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `xia0ne`
- Source Location: `hots.ts`
- Source Module: `_None_`

## Description
牛客热榜，包括热议话题和全站热贴

## Parameters
- `type`: 热榜类型，`1` 指热议话题，`2` 指全站热贴，默认为 `1`


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
  - `mnowpick.nowcoder.com/m/discuss/hot`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "牛客热榜，包括热议话题和全站热贴",
  "example": "/nowcoder/hots/1?limit=20",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "hots.ts",
  "maintainers": [
    "xia0ne"
  ],
  "name": "热榜",
  "parameters": {
    "type": "热榜类型，`1` 指热议话题，`2` 指全站热贴，默认为 `1`"
  },
  "path": "/hots/:type?",
  "radar": [
    {
      "source": [
        "mnowpick.nowcoder.com/m/discuss/hot"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "nowcoder.com/"
}
```
