# 中南大学 - 校长信箱

## Coverage
`index-only`

## Route
- Namespace: `csu`
- Namespace Name: `中南大学`
- Route Path: `/csu/mail/:type?`
- Route Name: `校长信箱`
- Example: `/csu/mail`
- URL: `career.csu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `j1g5awi`
- Source Location: `mail.ts`
- Source Module: `_None_`

## Description
| 类型 | 校长信箱 | 党委信箱 |
| ---- | -------- | -------- |
| 参数 | 01       | 02       |

## Parameters
- `type`: 类型


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
    "university"
  ],
  "description": "| 类型 | 校长信箱 | 党委信箱 |\n| ---- | -------- | -------- |\n| 参数 | 01       | 02       |",
  "example": "/csu/mail",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "mail.ts",
  "maintainers": [
    "j1g5awi"
  ],
  "name": "校长信箱",
  "parameters": {
    "type": "类型"
  },
  "path": "/mail/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "中南大学学校信箱 - 校长信箱 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "81350858120764416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://oa.csu.edu.cn/mailbox/NoAuth/MailList_Pub?tp=01",
      "title": "中南大学学校信箱 - 校长信箱",
      "type": "feed",
      "url": "rsshub://csu/mail"
    }
  ]
}
```
