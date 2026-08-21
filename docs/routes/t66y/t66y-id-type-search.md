# 草榴社区 - 分区帖子

## Coverage
`index-only`

## Route
- Namespace: `t66y`
- Namespace Name: `草榴社区`
- Route Path: `/t66y/:id/:type?/:search?`
- Route Name: `分区帖子`
- Example: `/t66y/20/2`
- URL: `t66y.com`
- Language: `_None_`
- Categories: `multimedia, popular`
- Maintainers: `zhboner`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
> 注意：并非所有的分区都有子类型，可以参考成人文学交流区的 `古典武侠` 这一子类型。

| 亚洲无码原创区 | 亚洲有码原创区 | 欧美原创区 | 动漫原创区 | 国产原创区 |
| -------------- | -------------- | ---------- | ---------- | ---------- |
| 2              | 15             | 4          | 5          | 25         |

| 中字原创区 | 转帖交流区 | HTTP 下载区 | 在线成人区 |
| ---------- | ---------- | ----------- | ---------- |
| 26         | 27         | 21          | 22         |

| 技术讨论区 | 新时代的我们 | 达盖尔的旗帜 | 成人文学交流 |
| ---------- | ------------ | ------------ | ------------ |
| 7          | 8            | 16           | 20           |

**主题过滤**

> 因为该类型无法搭配子类型使用，所以使用时 `type` 子类型需使用 `-999` 占位

| 今日主题 | 热门主题 | 精华主题 | 原创主题 | 今日新作 |
| -------- | -------- | -------- | -------- | -------- |
| today    | hot      | digest   | 1        | 2        |

## Parameters
- `id`: 分区 id, 可在分区页 URL 中找到
- `type`: 类型 id, 可在分区类型过滤后的 URL 中找到
- `search`: 主题类型筛选，可在分区主题类型筛选后的 URL 中找到，默认为 `today`


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
    "multimedia",
    "popular"
  ],
  "description": "> 注意：并非所有的分区都有子类型，可以参考成人文学交流区的 `古典武侠` 这一子类型。\n\n| 亚洲无码原创区 | 亚洲有码原创区 | 欧美原创区 | 动漫原创区 | 国产原创区 |\n| -------------- | -------------- | ---------- | ---------- | ---------- |\n| 2              | 15             | 4          | 5          | 25         |\n\n| 中字原创区 | 转帖交流区 | HTTP 下载区 | 在线成人区 |\n| ---------- | ---------- | ----------- | ---------- |\n| 26         | 27         | 21          | 22         |\n\n| 技术讨论区 | 新时代的我们 | 达盖尔的旗帜 | 成人文学交流 |\n| ---------- | ------------ | ------------ | ------------ |\n| 7          | 8            | 16           | 20           |\n\n**主题过滤**\n\n> 因为该类型无法搭配子类型使用，所以使用时 `type` 子类型需使用 `-999` 占位\n\n| 今日主题 | 热门主题 | 精华主题 | 原创主题 | 今日新作 |\n| -------- | -------- | -------- | -------- | -------- |\n| today    | hot      | digest   | 1        | 2        |",
  "example": "/t66y/20/2",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 25417,
  "location": "index.ts",
  "maintainers": [
    "zhboner"
  ],
  "name": "分区帖子",
  "parameters": {
    "id": "分区 id, 可在分区页 URL 中找到",
    "search": "主题类型筛选，可在分区主题类型筛选后的 URL 中找到，默认为 `today`",
    "type": "类型 id, 可在分区类型过滤后的 URL 中找到"
  },
  "path": "/:id/:type?/:search?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "[今日主题] 技術討論區 | 草榴社區 - t66y.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41719104290720768",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.t66y.com/thread0806.php?fid=7&search=today",
      "title": "[今日主题] 技術討論區 | 草榴社區 - t66y.com",
      "type": "feed",
      "url": "rsshub://t66y/7"
    },
    {
      "description": "[今日主题] 達蓋爾的旗幟 | 草榴社區 - t66y.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "43210762934293504",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.t66y.com/thread0806.php?fid=16&search=today",
      "title": "[今日主题] 達蓋爾的旗幟 | 草榴社區 - t66y.com",
      "type": "feed",
      "url": "rsshub://t66y/16"
    }
  ]
}
```
