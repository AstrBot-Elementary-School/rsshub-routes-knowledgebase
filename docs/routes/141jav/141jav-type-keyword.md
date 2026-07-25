# 141JAV - 通用

## Coverage
`index-only`

## Route
- Namespace: `141jav`
- Namespace Name: `141JAV`
- Route Path: `/141jav/:type/:keyword{.+}?`
- Route Name: `通用`
- Example: `_None_`
- URL: `141jav.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `cgkings, nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
**类型**

| 最新 | 热门    | 随机   | 指定演员 | 指定标签 | 日期 |
| ---- | ------- | ------ | -------- | -------- | ---- |
| new  | popular | random | actress  | tag      | date |

**关键词**

| 空 | 日期范围    | 演员名       | 标签名         | 年月日     |
| -- | ----------- | ------------ | -------------- | ---------- |
|    | 7 / 30 / 60 | Yua%20Mikami | Adult%20Awards | 2020/07/30 |

**示例说明**

- `/141jav/new`

  仅当类型为 `new` `popular` 或 `random` 时关键词为 **空**

- `/141jav/popular/30`

  `popular` `random` 类型的关键词可填写 `7` `30` 或 `60` 三个 **日期范围** 之一，分别对应 **7 天**、**30 天** 或 **60 天内**

- `/141jav/actress/Yua%20Mikami`

  `actress` 类型的关键词必须填写 **演员名** ，可在 [此处](https://141jav.com/actress/) 演员单页链接中获取

- `/141jav/tag/Adult%20Awards`

  `tag` 类型的关键词必须填写 **标签名** 且标签中的 `/` 必须替换为 `%2F` ，可在 [此处](https://141jav.com/tag/) 标签单页链接中获取

- `/141jav/date/2020/07/30`

  `date` 类型的关键词必须填写 **日期 (年 / 月 / 日)**

## Parameters
- `type`: 类型，可查看下表的类型说明
- `keyword`: 关键词，可查看下表的关键词说明


## Features
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "**类型**\n\n| 最新 | 热门    | 随机   | 指定演员 | 指定标签 | 日期 |\n| ---- | ------- | ------ | -------- | -------- | ---- |\n| new  | popular | random | actress  | tag      | date |\n\n**关键词**\n\n| 空 | 日期范围    | 演员名       | 标签名         | 年月日     |\n| -- | ----------- | ------------ | -------------- | ---------- |\n|    | 7 / 30 / 60 | Yua%20Mikami | Adult%20Awards | 2020/07/30 |\n\n**示例说明**\n\n- `/141jav/new`\n\n  仅当类型为 `new` `popular` 或 `random` 时关键词为 **空**\n\n- `/141jav/popular/30`\n\n  `popular` `random` 类型的关键词可填写 `7` `30` 或 `60` 三个 **日期范围** 之一，分别对应 **7 天**、**30 天** 或 **60 天内**\n\n- `/141jav/actress/Yua%20Mikami`\n\n  `actress` 类型的关键词必须填写 **演员名** ，可在 [此处](https://141jav.com/actress/) 演员单页链接中获取\n\n- `/141jav/tag/Adult%20Awards`\n\n  `tag` 类型的关键词必须填写 **标签名** 且标签中的 `/` 必须替换为 `%2F` ，可在 [此处](https://141jav.com/tag/) 标签单页链接中获取\n\n- `/141jav/date/2020/07/30`\n\n  `date` 类型的关键词必须填写 **日期 (年 / 月 / 日)**",
  "features": {
    "nsfw": true
  },
  "heat": 808,
  "location": "index.tsx",
  "maintainers": [
    "cgkings",
    "nczitzk"
  ],
  "name": "通用",
  "parameters": {
    "keyword": "关键词，可查看下表的关键词说明",
    "type": "类型，可查看下表的类型说明"
  },
  "path": "/:type/:keyword{.+}?",
  "topFeeds": [
    {
      "description": "141JAV - Popular (30 days) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "54839446413188096",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.141jav.com/popular/30",
      "title": "141JAV - Popular (30 days)",
      "type": "feed",
      "url": "rsshub://141jav/popular/30"
    },
    {
      "description": "141JAV - New - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "53022189134482432",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.141jav.com/new",
      "title": "141JAV - New",
      "type": "feed",
      "url": "rsshub://141jav/new"
    }
  ]
}
```
