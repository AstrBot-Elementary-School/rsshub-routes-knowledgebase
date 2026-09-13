# 电鸭社区 - 分类文章

## Coverage
`index-only`

## Route
- Namespace: `eleduck`
- Namespace Name: `电鸭社区`
- Route Path: `/eleduck/posts/:id?`
- Route Name: `分类文章`
- Example: `/eleduck/posts/4`
- URL: `eleduck.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `running-grass`
- Source Location: `posts.ts`
- Source Module: `_None_`

## Description
| id | 分类     |
| -- | -------- |
| 0  | 全部     |
| 1  | 讨论     |
| 2  | 分享     |
| 3  | 露个脸   |
| 4  | 访谈故事 |
| 5  | 招聘     |
| 10 | 海外移民 |
| 12 | 英语     |
| 14 | 电鸭官方 |
| 15 | 独立产品 |
| 17 | 闲话开源 |
| 19 | Web3     |
| 21 | 设计     |
| 22 | 人才库   |
| 23 | Upwork   |
| 24 | 经验课   |

## Parameters
- `id`: 分类id,可以论坛的URL找到，默认为全部


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
    "bbs"
  ],
  "description": "| id | 分类     |\n| -- | -------- |\n| 0  | 全部     |\n| 1  | 讨论     |\n| 2  | 分享     |\n| 3  | 露个脸   |\n| 4  | 访谈故事 |\n| 5  | 招聘     |\n| 10 | 海外移民 |\n| 12 | 英语     |\n| 14 | 电鸭官方 |\n| 15 | 独立产品 |\n| 17 | 闲话开源 |\n| 19 | Web3     |\n| 21 | 设计     |\n| 22 | 人才库   |\n| 23 | Upwork   |\n| 24 | 经验课   |",
  "example": "/eleduck/posts/4",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 85,
  "location": "posts.ts",
  "maintainers": [
    "running-grass"
  ],
  "name": "分类文章",
  "parameters": {
    "id": "分类id,可以论坛的URL找到，默认为全部"
  },
  "path": "/posts/:id?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "电鸭社区的文章,栏目为全部 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62423890812546048",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://eleduck.com/categories/0",
      "title": "电鸭社区的文章--全部",
      "type": "feed",
      "url": "rsshub://eleduck/posts"
    },
    {
      "description": "电鸭社区的文章,栏目为全部 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41709703529858048",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://eleduck.com/categories/0",
      "title": "电鸭社区的文章--全部",
      "type": "feed",
      "url": "rsshub://eleduck/posts/0"
    }
  ]
}
```
