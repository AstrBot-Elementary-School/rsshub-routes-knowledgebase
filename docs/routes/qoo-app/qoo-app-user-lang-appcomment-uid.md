# QooApp - User Game Comments

## Coverage
`index-only`

## Route
- Namespace: `qoo-app`
- Namespace Name: `QooApp`
- Route Path: `/qoo-app/user/:lang/appComment/:uid`
- Route Name: `User Game Comments`
- Example: `/qoo-app/user/en/appComment/35399143`
- URL: `apps.qoo-app.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `TonyRL`
- Source Location: `user/app-comment.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `lang`: Language, see the table above, empty means `中文`
- `uid`: User ID, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
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
    "anime"
  ],
  "example": "/qoo-app/user/en/appComment/35399143",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "user/app-comment.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "User Game Comments",
  "parameters": {
    "lang": "Language, see the table above, empty means `中文`",
    "uid": "User ID, can be found in URL"
  },
  "path": [
    "/user/:lang/appComment/:uid",
    "/user/appComment/:uid"
  ],
  "topFeeds": []
}
```
