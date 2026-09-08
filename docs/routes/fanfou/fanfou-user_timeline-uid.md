# 饭否 - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `fanfou`
- Namespace Name: `饭否`
- Route Path: `/fanfou/user_timeline/:uid`
- Route Name: `用户动态`
- Example: `/fanfou/user_timeline/wangxing`
- URL: `fanfou.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `junbaor`
- Source Location: `user-timeline.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户的uid


## Features
- `requireConfig`: [{"description": "饭否 Consumer Key", "name": "FANFOU_CONSUMER_KEY"}, {"description": "饭否 Consumer Secret", "name": "FANFOU_CONSUMER_SECRET"}, {"description": "饭否用户名", "name": "FANFOU_USERNAME"}, {"description": "饭否密码", "name": "FANFOU_PASSWORD"}]

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/fanfou/user_timeline/wangxing",
  "features": {
    "requireConfig": [
      {
        "description": "饭否 Consumer Key",
        "name": "FANFOU_CONSUMER_KEY"
      },
      {
        "description": "饭否 Consumer Secret",
        "name": "FANFOU_CONSUMER_SECRET"
      },
      {
        "description": "饭否用户名",
        "name": "FANFOU_USERNAME"
      },
      {
        "description": "饭否密码",
        "name": "FANFOU_PASSWORD"
      }
    ]
  },
  "heat": 2,
  "location": "user-timeline.ts",
  "maintainers": [
    "junbaor"
  ],
  "name": "用户动态",
  "parameters": {
    "uid": "用户的uid"
  },
  "path": "/user_timeline/:uid",
  "topFeeds": [
    {
      "description": "饭友经典语录的饭否 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1099515408919953413",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://fanfou.com/fyjdyl",
      "title": "饭友经典语录的饭否",
      "type": "feed",
      "url": "rsshub://fanfou/user_timeline/fyjdyl"
    },
    {
      "description": "李总好的饭否 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1099515408919953410",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://fanfou.com/%E6%9D%8E%E6%80%BB%E5%A5%BD",
      "title": "李总好的饭否",
      "type": "feed",
      "url": "rsshub://fanfou/user_timeline/%E6%9D%8E%E6%80%BB%E5%A5%BD"
    }
  ]
}
```
