# 南方都市报 - 奥一网

## Coverage
`index-only`

## Route
- Namespace: `oeeee`
- Namespace Name: `南方都市报`
- Route Path: `/oeeee/web/:channel`
- Route Name: `奥一网`
- Example: `/oeeee/web/170`
- URL: `oeeee.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TimWu007`
- Source Location: `web.ts`
- Source Module: `_None_`

## Description
- 若在桌面端打开奥一网栏目页（如 `https://www.oeeee.com/api/channel.php?s=/index/index/channel/gz`），可查看该页源代码，搜索 `OECID`。
- 若在移动端打开奥一网栏目页（格式例：`https://m.oeeee.com/m.php?s=/m2/channel&channel_id=169`），即可从 url 中获取。需注意的是，如果该栏目页的 url 格式为 `https://m.oeeee.com/detailChannel_indexData.html?channel_id=266` ，则 `266` 并非为本路由可用的频道 ID，建议从桌面端获取。

## Parameters
- `channel`: 频道 ID


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
    "traditional-media"
  ],
  "description": "- 若在桌面端打开奥一网栏目页（如 `https://www.oeeee.com/api/channel.php?s=/index/index/channel/gz`），可查看该页源代码，搜索 `OECID`。\n- 若在移动端打开奥一网栏目页（格式例：`https://m.oeeee.com/m.php?s=/m2/channel&channel_id=169`），即可从 url 中获取。需注意的是，如果该栏目页的 url 格式为 `https://m.oeeee.com/detailChannel_indexData.html?channel_id=266` ，则 `266` 并非为本路由可用的频道 ID，建议从桌面端获取。",
  "example": "/oeeee/web/170",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 18,
  "location": "web.ts",
  "maintainers": [
    "TimWu007"
  ],
  "name": "奥一网",
  "parameters": {
    "channel": "频道 ID"
  },
  "path": "/web/:channel",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "南方都市报奥一网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "150755089712076808",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.oeeee.com/api/channel.php?s=/index/index/channel/depth",
      "title": "南方都市报奥一网",
      "type": "feed",
      "url": "rsshub://oeeee/web/168"
    },
    {
      "description": "南方都市报奥一网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "150755089712076802",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.oeeee.com/api/channel.php?s=/index/index/channel/atsight",
      "title": "南方都市报奥一网",
      "type": "feed",
      "url": "rsshub://oeeee/web/588"
    }
  ]
}
```
