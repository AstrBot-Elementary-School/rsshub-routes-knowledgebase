# 掘金 - 用户文章

## Coverage
`index-only`

## Route
- Namespace: `juejin`
- Namespace Name: `掘金`
- Route Path: `/juejin/posts/:id`
- Route Name: `用户文章`
- Example: `/juejin/posts/3051900006845944`
- URL: `juejin.cn`
- Language: `_None_`
- Categories: `programming, popular`
- Maintainers: `Maecenas`
- Source Location: `posts.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 用户 id, 可在用户页 URL 中找到


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
  - `juejin.cn/user/:id`
  - `juejin.cn/user/:id/posts`

## Raw JSON
```json
{
  "categories": [
    "programming",
    "popular"
  ],
  "example": "/juejin/posts/3051900006845944",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2167,
  "location": "posts.ts",
  "maintainers": [
    "Maecenas"
  ],
  "name": "用户文章",
  "parameters": {
    "id": "用户 id, 可在用户页 URL 中找到"
  },
  "path": "/posts/:id",
  "radar": [
    {
      "source": [
        "juejin.cn/user/:id",
        "juejin.cn/user/:id/posts"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "字节跳动的技术实践分享 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41511702474276869",
      "image": "https://p1-jj.byteimg.com/tos-cn-i-t2oaga2asx/gold-user-assets/2018/7/16/164a1386a8b82dbd~tplv-t2oaga2asx-image.image",
      "ownerUserId": null,
      "siteUrl": "https://juejin.cn/user/1838039172387262/posts",
      "title": "掘金专栏-字节跳动技术团队",
      "type": "feed",
      "url": "rsshub://juejin/posts/1838039172387262"
    },
    {
      "description": "《React 通关秘籍》《Nest 通关秘籍》《前端调试通关秘籍》《TypeScript 类型体操通关秘籍》等 7 本小册作者，最近在“神光的幸福生活”公众号更《前端转 Agent 全栈通关秘籍》 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41215011978385459",
      "image": "https://p9-passport.byteacctimg.com/img/user-avatar/4e9e751e2b32fb8afbbf559a296ccbf2~300x300.image",
      "ownerUserId": null,
      "siteUrl": "https://juejin.cn/user/2788017216685118/posts",
      "title": "掘金专栏-神光的幸福生活公号",
      "type": "feed",
      "url": "rsshub://juejin/posts/2788017216685118"
    }
  ]
}
```
