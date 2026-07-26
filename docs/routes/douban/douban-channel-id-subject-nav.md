# 豆瓣 - 频道书影音

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/channel/:id/subject/:nav`
- Route Name: `频道书影音`
- Example: `/douban/channel/30168934/subject/0`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `umm233`
- Source Location: `channel/subject.ts`
- Source Module: `_None_`

## Description
| 电影 | 电视剧 | 图书 | 唱片 |
| ---- | ------ | ---- | ---- |
| 0    | 1      | 2    | 3    |

## Parameters
- `id`: 频道id
- `nav`: 书影音分类


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
    "social-media"
  ],
  "description": "| 电影 | 电视剧 | 图书 | 唱片 |\n| ---- | ------ | ---- | ---- |\n| 0    | 1      | 2    | 3    |",
  "example": "/douban/channel/30168934/subject/0",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 22,
  "location": "channel/subject.ts",
  "maintainers": [
    "umm233"
  ],
  "name": "频道书影音",
  "parameters": {
    "id": "频道id",
    "nav": "书影音分类"
  },
  "path": "/channel/:id/subject/:nav",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "豆瓣美剧频道书影音下的电视剧推荐 - Powered by RSSHub",
      "errorAt": "2026-07-22T13:38:05.829Z",
      "errorMessage": "[GET] \"https://m.douban.com/rexxar/api/v2/elessar/channel/27622657\": 500 Internal Server Error\n",
      "id": "76960076233678848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.douban.com/subject/27622657",
      "title": "豆瓣美剧频道-电视剧推荐",
      "type": "feed",
      "url": "rsshub://douban/channel/27622657/subject/1"
    },
    {
      "description": "豆瓣历史频道书影音下的电影推荐 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61440669496322048",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.douban.com/subject/30168934",
      "title": "豆瓣历史频道-电影推荐",
      "type": "feed",
      "url": "rsshub://douban/channel/30168934/subject/0"
    }
  ]
}
```
