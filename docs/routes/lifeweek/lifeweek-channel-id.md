# 三联生活周刊 - Unknown

## Coverage
`index-only`

## Route
- Namespace: `lifeweek`
- Namespace Name: `三联生活周刊`
- Route Path: `/lifeweek/channel/:id`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `lifeweek.com.cn`
- Language: `_None_`
- Categories: `other`
- Maintainers: `None`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `lifeweek.com.cn/column/:channel`
- `target`: `/channel/:channel`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "heat": 135,
  "location": "channel.ts",
  "maintainers": [],
  "name": "Unknown",
  "path": "/channel/:id",
  "radar": [
    {
      "source": [
        "lifeweek.com.cn/column/:channel"
      ],
      "target": "/channel/:channel"
    }
  ],
  "topFeeds": [
    {
      "description": "文化 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74705665643397120",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lifeweek.com.cn/column/4",
      "title": "文化",
      "type": "feed",
      "url": "rsshub://lifeweek/channel/4"
    },
    {
      "description": "经济 - Powered by RSSHub",
      "errorAt": "2026-07-24T01:11:07.943Z",
      "errorMessage": "[GET] \"https://www.lifeweek.com.cn/api/userWebFollow/getFollowTagContentList?type=3&sort=2&tagId=3\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 211.162.165.44:443, 211.162.165.45:443, 211.162.165.46:443, 211.162.165.39:443, 211.162.165.40:443, 211.162.165.41:443, 211.162.165.42:443, 211.162.165.43:443, timeout: 10000ms))\n",
      "id": "77268471866082304",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lifeweek.com.cn/column/3",
      "title": "经济",
      "type": "feed",
      "url": "rsshub://lifeweek/channel/3"
    }
  ]
}
```
