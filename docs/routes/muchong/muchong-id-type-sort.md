# 小木虫论坛 - 分类

## Coverage
`index-only`

## Route
- Namespace: `muchong`
- Namespace Name: `小木虫论坛`
- Route Path: `/muchong/:id/:type?/:sort?`
- Route Name: `分类`
- Example: `/muchong/290`
- URL: `muchong.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
尚不支持需要登录访问的版块
:::

## Parameters
- `id`: 板块 id，可在板块页 URL 中找到
- `type`: 子类别 id，可在板块页导航栏中找到，默认为 `all` 即 全部
- `sort`: 排序，可选 `order-tid` 即 发表排序，默认为 回帖排序


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "::: tip\n尚不支持需要登录访问的版块\n:::",
  "example": "/muchong/290",
  "heat": 4,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "id": "板块 id，可在板块页 URL 中找到",
    "sort": "排序，可选 `order-tid` 即 发表排序，默认为 回帖排序",
    "type": "子类别 id，可在板块页导航栏中找到，默认为 `all` 即 全部"
  },
  "path": "/:id/:type?/:sort?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "海归之家 - 出国留学区 - 小木虫论坛 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "177651896292777998",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://muchong.com/f-428-1",
      "title": "海归之家 - 出国留学区 - 小木虫论坛",
      "type": "feed",
      "url": "rsshub://muchong/428"
    },
    {
      "description": "论文投稿 - 学术交流区 - 小木虫论坛 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "177651896292777999",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://muchong.com/f-125-1",
      "title": "论文投稿 - 学术交流区 - 小木虫论坛",
      "type": "feed",
      "url": "rsshub://muchong/125"
    }
  ]
}
```
