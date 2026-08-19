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
  "heat": 91,
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
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "[10月] 求片求助貼 - 技術討論區 | 草榴社區 - t66y.com - Powered by RSSHub",
      "errorAt": "2026-07-09T12:39:39.441Z",
      "errorMessage": "[GET] \"https://www.t66y.com/read.php?tid=6525269\": <no response> fetch failed\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "65635145638340608",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "[10月] 求片求助貼 - 技術討論區 | 草榴社區 - t66y.com",
      "type": "feed",
      "url": "rsshub://t66y/post/6525269"
    },
    {
      "description": "[現代奇幻] 有一种巧合叫租在隔壁（下） - 成人文學交流區 | 草榴社區 - t66y.com - Powered by RSSHub",
      "errorAt": "2026-07-09T12:04:23.977Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "60209348426006528",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "[現代奇幻] 有一种巧合叫租在隔壁（下） - 成人文學交流區 | 草榴社區 - t66y.com",
      "type": "feed",
      "url": "rsshub://t66y/post/3286088"
    }
  ]
}
```
