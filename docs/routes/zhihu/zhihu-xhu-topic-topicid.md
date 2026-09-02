# 知乎 - xhu - 话题

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/xhu/topic/:topicId`
- Route Name: `xhu - 话题`
- Example: `/zhihu/xhu/topic/19566035`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `JimenezLi`
- Source Location: `xhu/topic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topicId`: 话题ID


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
  - `www.zhihu.com/topic/:topicId/:type`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/xhu/topic/19566035",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 28,
  "location": "xhu/topic.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "name": "xhu - 话题",
  "parameters": {
    "topicId": "话题ID"
  },
  "path": "/xhu/topic/:topicId",
  "radar": [
    {
      "source": [
        "www.zhihu.com/topic/:topicId/:type"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "知乎话题-19584076 - Powered by RSSHub",
      "errorAt": "2025-07-22T05:21:43.362Z",
      "errorMessage": "[GET] \"https://api.zhihuvvv.workers.dev/guests/token\": 401 Unauthorized\n",
      "id": "71400099416162304",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/topic/19584076/newest",
      "title": "知乎话题-19584076",
      "type": "feed",
      "url": "rsshub://zhihu/xhu/topic/19584076"
    },
    {
      "description": "知乎话题-21197624 - Powered by RSSHub",
      "errorAt": "2025-07-31T11:47:20.831Z",
      "errorMessage": "[GET] \"https://api.zhihuvvv.workers.dev/guests/token\": 401 Unauthorized\n",
      "id": "79400515584645165",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/topic/21197624/newest",
      "title": "知乎话题-21197624",
      "type": "feed",
      "url": "rsshub://zhihu/xhu/topic/21197624"
    }
  ]
}
```
