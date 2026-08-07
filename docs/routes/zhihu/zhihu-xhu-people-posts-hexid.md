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
      "description": "哎较，据应，效炕，伙竭 - Powered by RSSHub",
      "errorAt": "2024-12-27T03:36:13.588Z",
      "errorMessage": "[GET] \"https://api.zhihuvvv.workers.dev/guests/token\": 401 Unauthorized\n",
      "id": "56220581110160384",
      "image": "https://pic1.zhimg.com/v2-01298fe87288c5c08e5f02a0e553aae6_l.jpg?source=d16d100b",
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/people/e709c8434b3cb85cb9c06c2c5e3703a5/posts",
      "title": "铁绘 的知乎文章",
      "type": "feed",
      "url": "rsshub://zhihu/xhu/people/posts/e709c8434b3cb85cb9c06c2c5e3703a5"
    },
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
    }
  ]
}
```
