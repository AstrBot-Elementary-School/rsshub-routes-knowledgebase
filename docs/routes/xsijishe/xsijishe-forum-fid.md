# 司机社 - 论坛

## Coverage
`index-only`

## Route
- Namespace: `xsijishe`
- Namespace Name: `司机社`
- Route Path: `/xsijishe/forum/:fid`
- Route Name: `论坛`
- Example: `/xsijishe/forum/51`
- URL: `xsijishe.com`
- Language: `_None_`
- Categories: `bbs, popular`
- Maintainers: `akynazh`
- Source Location: `forum.ts`
- Source Module: `_None_`

## Description
::: tip 关于子论坛 id 的获取方法
`/xsijishe/forum/51` 对应于论坛 `https://xsijishe.com/forum-51-1.html`，这个论坛的 fid 为 51，也就是 `forum-{fid}-1` 中的 fid。
:::

## Parameters
- `fid`: 子论坛 id


## Features
- `requireConfig`: [{"description": "", "name": "XSIJISHE_COOKIE"}, {"description": "", "name": "XSIJISHE_USER_AGENT"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
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
    "bbs",
    "popular"
  ],
  "description": "::: tip 关于子论坛 id 的获取方法\n`/xsijishe/forum/51` 对应于论坛 `https://xsijishe.com/forum-51-1.html`，这个论坛的 fid 为 51，也就是 `forum-{fid}-1` 中的 fid。\n:::",
  "example": "/xsijishe/forum/51",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "",
        "name": "XSIJISHE_COOKIE"
      },
      {
        "description": "",
        "name": "XSIJISHE_USER_AGENT"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2142,
  "location": "forum.ts",
  "maintainers": [
    "akynazh"
  ],
  "name": "论坛",
  "parameters": {
    "fid": "子论坛 id"
  },
  "path": "/forum/:fid",
  "topFeeds": [
    {
      "description": "司机社国产视频论坛 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41708590536881152",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xsijishe.com/forum-48-1.html",
      "title": "司机社国产视频论坛",
      "type": "feed",
      "url": "rsshub://xsijishe/forum/48"
    },
    {
      "description": "司机社日本AV论坛 - Powered by RSSHub",
      "errorAt": "2026-08-15T13:38:40.577Z",
      "errorMessage": "200 ",
      "id": "55159238633029632",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xsijishe.com/forum-51-1.html",
      "title": "司机社日本AV论坛",
      "type": "feed",
      "url": "rsshub://xsijishe/forum/51"
    }
  ]
}
```
