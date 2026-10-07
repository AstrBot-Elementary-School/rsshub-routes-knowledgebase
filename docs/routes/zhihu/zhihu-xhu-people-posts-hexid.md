# 知乎 - xhu - 用户文章

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/xhu/people/posts/:hexId`
- Route Name: `xhu - 用户文章`
- Example: `/zhihu/xhu/people/posts/246e6cf44e94cefbf4b959cb5042bc91`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `JimenezLi`
- Source Location: `xhu/posts.ts`
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
  "example": "/zhihu/xhu/people/posts/246e6cf44e94cefbf4b959cb5042bc91",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "xhu/posts.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "name": "xhu - 用户文章",
  "parameters": {
    "hexId": "用户的 16 进制 id，获取方式同 [xhu - 用户动态](#zhi-hu-xhu-yong-hu-dong-tai)"
  },
  "path": "/xhu/people/posts/:hexId",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "角钩轮【猪贝崩跺SYS Tech】 - Powered by RSSHub",
      "errorAt": "2024-12-27T06:53:36.264Z",
      "errorMessage": "[GET] \"https://api.zhihuvvv.workers.dev/guests/token\": 401 Unauthorized\n",
      "id": "56221874901949440",
      "image": "https://pica.zhimg.com/v2-3da4bc24ef461eebe98b23c49745cad5_l.jpg?source=d16d100b",
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/people/9e0d17057014ec05e852157d10f8e542/posts",
      "title": "螺节跳动SYS Tech 的知乎文章",
      "type": "feed",
      "url": "rsshub://zhihu/xhu/people/posts/9e0d17057014ec05e852157d10f8e542"
    },
    {
      "description": null,
      "errorAt": "2025-07-04T18:37:16.421Z",
      "errorMessage": "[GET] \"https://api.zhihuvvv.workers.dev/guests/token\": 401 Unauthorized\n",
      "id": "164021701195543557",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://zhihu/xhu/people/posts/9819f6938be0d3bb133ad0151eefd188"
    }
  ]
}
```
