# 饭否 - 饭否搜索

## Coverage
`index-only`

## Route
- Namespace: `fanfou`
- Namespace Name: `饭否`
- Route Path: `/fanfou/public_timeline/:keyword`
- Route Name: `饭否搜索`
- Example: `/fanfou/public_timeline/RSSHub`
- URL: `fanfou.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `junbaor`
- Source Location: `public-timeline.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 关键字


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
  "example": "/fanfou/public_timeline/RSSHub",
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
  "heat": 0,
  "location": "public-timeline.ts",
  "maintainers": [
    "junbaor"
  ],
  "name": "饭否搜索",
  "parameters": {
    "keyword": "关键字"
  },
  "path": "/public_timeline/:keyword",
  "topFeeds": []
}
```
