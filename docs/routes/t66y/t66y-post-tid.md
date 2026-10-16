# 草榴社区 - 帖子跟踪

## Coverage
`index-only`

## Route
- Namespace: `t66y`
- Namespace Name: `草榴社区`
- Route Path: `/t66y/post/:tid`
- Route Name: `帖子跟踪`
- Example: `/t66y/post/3286088`
- URL: `t66y.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `cnzgray`
- Source Location: `post.ts`
- Source Module: `_None_`

## Description
::: tip
帖子 id 查找办法:

打开想跟踪的帖子，比如：`https://t66y.com/htm_data/20/1811/3286088.html` 其中 `3286088` 就是帖子 id。
:::

## Parameters
- `tid`: 帖子 id, 可在帖子 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\n帖子 id 查找办法:\n\n打开想跟踪的帖子，比如：`https://t66y.com/htm_data/20/1811/3286088.html` 其中 `3286088` 就是帖子 id。\n:::",
  "example": "/t66y/post/3286088",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 93,
  "location": "post.ts",
  "maintainers": [
    "cnzgray"
  ],
  "name": "帖子跟踪",
  "parameters": {
    "tid": "帖子 id, 可在帖子 URL 中找到"
  },
  "path": "/post/:tid",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "[現代奇幻] 有一种巧合叫租在隔壁（下） - 成人文學交流區 | 草榴社區 - t66y.com - Powered by RSSHub",
      "errorAt": "2026-07-09T12:04:23.977Z",
      "errorMessage": "[GET] \"https://www.t66y.com/read.php?tid=3286088\": 403 Forbidden\n",
      "id": "60209348426006528",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "[現代奇幻] 有一种巧合叫租在隔壁（下） - 成人文學交流區 | 草榴社區 - t66y.com",
      "type": "feed",
      "url": "rsshub://t66y/post/3286088"
    },
    {
      "description": "[10月] 求片求助貼 - 技術討論區 | 草榴社區 - t66y.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65635145638340608",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.t66y.com/htm_data/2409/7/6525269.html",
      "title": "[10月] 求片求助貼 - 技術討論區 | 草榴社區 - t66y.com",
      "type": "feed",
      "url": "rsshub://t66y/post/6525269"
    }
  ]
}
```
