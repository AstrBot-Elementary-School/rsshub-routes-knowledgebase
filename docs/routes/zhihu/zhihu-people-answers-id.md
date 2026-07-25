# 知乎 - 用户回答

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/people/answers/:id`
- Route Name: `用户回答`
- Example: `/zhihu/people/answers/diygod`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod, prnake`
- Source Location: `answers.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 作者 id，可在用户主页 URL 中找到


## Features
- `requireConfig`: [{"description": "", "name": "ZHIHU_COOKIES", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.zhihu.com/people/:id/answers`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/people/answers/diygod",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "ZHIHU_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 298,
  "location": "answers.ts",
  "maintainers": [
    "DIYgod",
    "prnake"
  ],
  "name": "用户回答",
  "parameters": {
    "id": "作者 id，可在用户主页 URL 中找到"
  },
  "path": "/people/answers/:id",
  "radar": [
    {
      "source": [
        "www.zhihu.com/people/:id/answers"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "q9adg的知乎回答 - Powered by RSSHub",
      "errorAt": "2025-08-16T15:03:36.399Z",
      "errorMessage": "[GET] \"https://www.zhihu.com/api/v4/members/kvxjr369f/answers?limit=7&include=data[*].is_normal,content\": 403 Forbidden\n",
      "id": "60696029890536448",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/people/kvxjr369f/answers",
      "title": "q9adg的知乎回答",
      "type": "feed",
      "url": "rsshub://zhihu/people/answers/kvxjr369f"
    },
    {
      "description": "王子君的知乎回答 - Powered by RSSHub",
      "errorAt": "2025-04-22T12:23:04.103Z",
      "errorMessage": "[GET] \"https://www.zhihu.com/api/v4/members/nogirlnotalk/answers?limit=7&include=data[*].is_normal,content\": 403 Forbidden\n",
      "id": "62090527887115299",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/people/nogirlnotalk/answers",
      "title": "王子君的知乎回答",
      "type": "feed",
      "url": "rsshub://zhihu/people/answers/nogirlnotalk"
    }
  ]
}
```
