# Bangumi 番组计划 - 条目的通用路由格式

## Coverage
`index-only`

## Route
- Namespace: `bangumi.tv`
- Namespace Name: `Bangumi 番组计划`
- Route Path: `/bangumi.tv/subject/:id/:type?/:showOriginalName?`
- Route Name: `条目的通用路由格式`
- Example: `/bangumi.tv/subject/328609/ep/true`
- URL: `bangumi.tv`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `JimenezLi`
- Source Location: `subject/index.ts`
- Source Module: `_None_`

## Description
::: warning
此通用路由仅用于对路由参数的描述，具体信息请查看下方与条目相关的路由
:::

## Parameters
- `id`: 条目 id, 在条目页面的地址栏查看
- `type`: 条目类型，可选值为 `ep`, `comments`, `blogs`, `topics`，默认为 `ep`
- `showOriginalName`: 显示番剧标题原名，可选值 0/1/false/true，默认为 false


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
  - `bgm.tv/subject/:id`
- `target`: `/subject/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "::: warning\n此通用路由仅用于对路由参数的描述，具体信息请查看下方与条目相关的路由\n:::",
  "example": "/bangumi.tv/subject/328609/ep/true",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "subject/index.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "name": "条目的通用路由格式",
  "parameters": {
    "id": "条目 id, 在条目页面的地址栏查看",
    "showOriginalName": "显示番剧标题原名，可选值 0/1/false/true，默认为 false",
    "type": "条目类型，可选值为 `ep`, `comments`, `blogs`, `topics`，默认为 `ep`"
  },
  "path": "/subject/:id/:type?/:showOriginalName?",
  "radar": [
    {
      "source": [
        "bgm.tv/subject/:id"
      ],
      "target": "/subject/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "作为网络吉他手“吉他英雄”而广受好评的后藤一里，在现实中却是个什么都不会的沟通障碍者。一里有着组建乐队的梦想，但因为不敢向人主动搭话而一直没有成功，直到一天在公园中被伊地知虹夏发现并邀请进入缺少吉他手的“结束乐队”。可是，完全没有和他人合作经历的一里，在人前完全发挥不出原本的实力。为了努力克服沟通障碍，一里与“结束乐队”的成员们一同开始努力…… - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "127649575170375680",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bgm.tv/subject/328609",
      "title": "ぼっち・ざ・ろっく！",
      "type": "feed",
      "url": "rsshub://bangumi.tv/subject/328609/ep/true"
    }
  ]
}
```
