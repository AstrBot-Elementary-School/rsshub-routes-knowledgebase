# Keep - 运动日记

## Coverage
`index-only`

## Route
- Namespace: `keep`
- Namespace Name: `Keep`
- Route Path: `/keep/user/:id`
- Route Name: `运动日记`
- Example: `/keep/user/556b02c1ab59390afea671ea`
- URL: `gotokeep.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Dectinc, DIYgod`
- Source Location: `user.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Keep 用户 id


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
  - `gotokeep.com/users/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/keep/user/556b02c1ab59390afea671ea",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 28,
  "location": "user.tsx",
  "maintainers": [
    "Dectinc",
    "DIYgod"
  ],
  "name": "运动日记",
  "parameters": {
    "id": "Keep 用户 id"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "gotokeep.com/users/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "肉丝__Rose 的 Keep 动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "160540878822200320",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://show.gotokeep.com/users/55d37984c4bf86048111b197",
      "title": "肉丝__Rose 的 Keep 动态",
      "type": "feed",
      "url": "rsshub://keep/user/55d37984c4bf86048111b197"
    },
    {
      "description": "senina22 的 Keep 动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "160541701301147648",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://show.gotokeep.com/users/5645d6be8476ac40762ff452",
      "title": "senina22 的 Keep 动态",
      "type": "feed",
      "url": "rsshub://keep/user/5645d6be8476ac40762ff452"
    }
  ]
}
```
