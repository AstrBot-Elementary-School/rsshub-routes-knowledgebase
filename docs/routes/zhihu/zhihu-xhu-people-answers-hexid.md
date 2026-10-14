# 知乎 - xhu - 用户回答

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/xhu/people/answers/:hexId`
- Route Name: `xhu - 用户回答`
- Example: `/zhihu/xhu/people/answers/246e6cf44e94cefbf4b959cb5042bc91`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `JimenezLi`
- Source Location: `xhu/answers.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `hexId`: 用户的 16 进制 id，获取方式同 [xhu - 用户动态](#zhi-hu-xhu-yong-hu-dong-tai)


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
  "example": "/zhihu/xhu/people/answers/246e6cf44e94cefbf4b959cb5042bc91",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "xhu/answers.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "name": "xhu - 用户回答",
  "parameters": {
    "hexId": "用户的 16 进制 id，获取方式同 [xhu - 用户动态](#zhi-hu-xhu-yong-hu-dong-tai)"
  },
  "path": "/xhu/people/answers/:hexId",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "于咬敢的知乎回答 - Powered by RSSHub",
      "errorAt": "2025-07-13T11:00:40.415Z",
      "errorMessage": "[GET] \"https://api.zhihuvvv.workers.dev/guests/token\": 401 Unauthorized\n",
      "id": "57319071807974400",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/people/246e6cf44e94cefbf4b959cb5042bc91/answers",
      "title": "于咬敢的知乎回答",
      "type": "feed",
      "url": "rsshub://zhihu/xhu/people/answers/246e6cf44e94cefbf4b959cb5042bc91"
    }
  ]
}
```
