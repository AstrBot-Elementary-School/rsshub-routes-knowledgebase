# Lofter - User

## Coverage
`index-only`

## Route
- Namespace: `lofter`
- Namespace Name: `Lofter`
- Route Path: `/lofter/user/:name?`
- Route Name: `User`
- Example: `/lofter/user/i`
- URL: `www.lofter.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `hondajojo, nczitzk, LucunJi`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: Lofter user name, can be found in the URL


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
  "example": "/lofter/user/i",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 306,
  "location": "user.ts",
  "maintainers": [
    "hondajojo",
    "nczitzk",
    "LucunJi"
  ],
  "name": "User",
  "parameters": {
    "name": "Lofter user name, can be found in the URL"
  },
  "path": "/user/:name?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "LOFTER官方博客 | LOFTER - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56435502271896576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://i.lofter.com/",
      "title": "LOFTER官方博客 | LOFTER",
      "type": "feed",
      "url": "rsshub://lofter/user"
    },
    {
      "description": "路人甲街拍 | LOFTER - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "83776600393458688",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://lurenjiajiepai.lofter.com/",
      "title": "路人甲街拍 | LOFTER",
      "type": "feed",
      "url": "rsshub://lofter/user/lurenjiajiepai"
    }
  ],
  "view": 0
}
```
