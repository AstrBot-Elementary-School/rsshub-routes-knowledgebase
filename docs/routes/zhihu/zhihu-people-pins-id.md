# 知乎 - 用户想法

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/people/pins/:id`
- Route Name: `用户想法`
- Example: `/zhihu/people/pins/kan-dan-45`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `xyqfer`
- Source Location: `pin/people.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 作者 id，可在用户主页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.zhihu.com/people/:id/pins`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/people/pins/kan-dan-45",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 69,
  "location": "pin/people.ts",
  "maintainers": [
    "xyqfer"
  ],
  "name": "用户想法",
  "parameters": {
    "id": "作者 id，可在用户主页 URL 中找到"
  },
  "path": "/people/pins/:id",
  "radar": [
    {
      "source": [
        "www.zhihu.com/people/:id/pins"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "王海的知乎想法 - Powered by RSSHub",
      "errorAt": "2026-06-27T10:29:22.098Z",
      "errorMessage": "[GET] \"https://api.zhihu.com/pins/wang-hai-33-67/moments?limit=10&offset=0\": 403 Forbidden\n",
      "id": "108005640078193664",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/people/wang-hai-33-67/pins",
      "title": "王海的知乎想法",
      "type": "feed",
      "url": "rsshub://zhihu/people/pins/wang-hai-33-67"
    },
    {
      "description": "00后富一代的知乎想法 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "111705971907407872",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/people/mei-hao-wei-lai-9-78-87/pins",
      "title": "00后富一代的知乎想法",
      "type": "feed",
      "url": "rsshub://zhihu/people/pins/mei-hao-wei-lai-9-78-87"
    }
  ]
}
```
