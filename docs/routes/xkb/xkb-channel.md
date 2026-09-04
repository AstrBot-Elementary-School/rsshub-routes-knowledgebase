# 新快报 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `xkb`
- Namespace Name: `新快报`
- Route Path: `/xkb/:channel`
- Route Name: `新闻`
- Example: `/xkb/350`
- URL: `xkb.com.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TimWu007`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
常用栏目 ID：

| 栏目名 | ID  |
| ------ | --- |
| 首页   | 350 |
| 重点   | 359 |
| 广州   | 353 |
| 湾区   | 360 |
| 天下   | 355 |

## Parameters
- `channel`: 栏目 ID，点击对应栏目后在地址栏找到


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
  "description": "常用栏目 ID：\n\n| 栏目名 | ID  |\n| ------ | --- |\n| 首页   | 350 |\n| 重点   | 359 |\n| 广州   | 353 |\n| 湾区   | 360 |\n| 天下   | 355 |",
  "example": "/xkb/350",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "index.tsx",
  "maintainers": [
    "TimWu007"
  ],
  "name": "新闻",
  "parameters": {
    "channel": "栏目 ID，点击对应栏目后在地址栏找到"
  },
  "path": "/:channel",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "新快报新快网 - 首页 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59112290766065664",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.xkb.com.cn/home?id=350",
      "title": "新快报新快网 - 首页",
      "type": "feed",
      "url": "rsshub://xkb/350"
    },
    {
      "description": "新快报新快网 - 重点 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "210608067387659264",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.xkb.com.cn/home?id=359",
      "title": "新快报新快网 - 重点",
      "type": "feed",
      "url": "rsshub://xkb/359"
    }
  ]
}
```
