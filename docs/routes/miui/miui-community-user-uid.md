# MIUI - 小米社区用户发帖

## Coverage
`index-only`

## Route
- Namespace: `miui`
- Namespace Name: `MIUI`
- Route Path: `/miui/community/user/:uid`
- Route Name: `小米社区用户发帖`
- Example: `/miui/community/user/1200057564`
- URL: `miui.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `abc1763613206`
- Source Location: `community/user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 小米用户 UID，可于网页版用户主页链接中 `uid` 项获取


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
  - `web.vip.miui.com/page/info/mio/mio/homePage`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/miui/community/user/1200057564",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 25,
  "location": "community/user.ts",
  "maintainers": [
    "abc1763613206"
  ],
  "name": "小米社区用户发帖",
  "parameters": {
    "uid": "小米用户 UID，可于网页版用户主页链接中 `uid` 项获取"
  },
  "path": "/community/user/:uid",
  "radar": [
    {
      "source": [
        "web.vip.miui.com/page/info/mio/mio/homePage"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "小米澎湃OS公告君 的发帖 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74458155910323200",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://web.vip.miui.com/page/info/mio/mio/homePage?uid=1200057564",
      "title": "小米社区 - 小米澎湃OS公告君 的发帖",
      "type": "feed",
      "url": "rsshub://miui/community/user/1200057564"
    },
    {
      "description": "文教授 的发帖 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "150139249615693824",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://web.vip.miui.com/page/info/mio/mio/homePage?uid=95045457",
      "title": "小米社区 - 文教授 的发帖",
      "type": "feed",
      "url": "rsshub://miui/community/user/95045457"
    }
  ]
}
```
