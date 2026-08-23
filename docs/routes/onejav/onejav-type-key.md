# OneJAV - OneJAV BT

## Coverage
`index-only`

## Route
- Namespace: `onejav`
- Namespace Name: `OneJAV`
- Route Path: `/onejav/:type/:key?`
- Route Name: `OneJAV BT`
- Example: `/onejav/popular/30`
- URL: `onejav.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `monsterxcn`
- Source Location: `one.ts`
- Source Module: `_None_`

## Description
**类型**

| 最新 | 热门    | 随机   | 指定演员 | 指定标签 | 指定日期 |
| ---- | ------- | ------ | -------- | -------- | -------- |
| new  | popular | random | actress  | tag      | day      |

**关键词**

| 空 | 日期范围    | 演员名       | 标签名         | 日期     |
| -- | ----------- | ------------ | -------------- | -------- |
|    | 7 / 30 / 60 | Yua%20Mikami | Adult%20Awards | YYYYMMDD |

**示例说明**

- `/onejav/new`

  仅当类型为 `new` `popular` 或 `random` 时关键词可为 **空**

- `/onejav/popular/30`

  `popular` `random` 类型的关键词可填写 `7` `30` 或 `60` 三个 **日期范围** 之一

- `/onejav/actress/Yua%20Mikami`

  `actress` 类型的关键词必须填写 **演员名** ，可在 [此处](https://onejav.com/actress/) 演员单页链接中获取

- `/onejav/tag/Adult%20Awards`

  `tag` 类型的关键词必须填写 **标签名** 且标签中的 `/` 必须替换为 `%2F` ，可在 [此处](https://onejav.com/tag/) 标签单页链接中获取

- `/onejav/day/20200730`

  `day` 类型的关键词必须填写 **日期** ，按照示例写成形如 `20200730` 的格式

## Parameters
- `type`: 类型
- `key`: 关键词


## Features
- `antiCrawler`: true
- `supportBT`: true
- `nsfw`: true

## Radar
### Rule 1
- `title`: `页面种子`
- `source`:
  - `onejav.com/:type`
  - `onejav.com/:type/:key`
  - `onejav.com/:type/:key/:morekey`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "**类型**\n\n| 最新 | 热门    | 随机   | 指定演员 | 指定标签 | 指定日期 |\n| ---- | ------- | ------ | -------- | -------- | -------- |\n| new  | popular | random | actress  | tag      | day      |\n\n**关键词**\n\n| 空 | 日期范围    | 演员名       | 标签名         | 日期     |\n| -- | ----------- | ------------ | -------------- | -------- |\n|    | 7 / 30 / 60 | Yua%20Mikami | Adult%20Awards | YYYYMMDD |\n\n**示例说明**\n\n- `/onejav/new`\n\n  仅当类型为 `new` `popular` 或 `random` 时关键词可为 **空**\n\n- `/onejav/popular/30`\n\n  `popular` `random` 类型的关键词可填写 `7` `30` 或 `60` 三个 **日期范围** 之一\n\n- `/onejav/actress/Yua%20Mikami`\n\n  `actress` 类型的关键词必须填写 **演员名** ，可在 [此处](https://onejav.com/actress/) 演员单页链接中获取\n\n- `/onejav/tag/Adult%20Awards`\n\n  `tag` 类型的关键词必须填写 **标签名** 且标签中的 `/` 必须替换为 `%2F` ，可在 [此处](https://onejav.com/tag/) 标签单页链接中获取\n\n- `/onejav/day/20200730`\n\n  `day` 类型的关键词必须填写 **日期** ，按照示例写成形如 `20200730` 的格式",
  "example": "/onejav/popular/30",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "supportBT": true
  },
  "heat": 0,
  "location": "one.ts",
  "maintainers": [
    "monsterxcn"
  ],
  "name": "OneJAV BT",
  "parameters": {
    "key": "关键词",
    "type": "类型"
  },
  "path": "/:type/:key?",
  "radar": [
    {
      "source": [
        "onejav.com/:type",
        "onejav.com/:type/:key",
        "onejav.com/:type/:key/:morekey"
      ],
      "title": "页面种子"
    }
  ],
  "topFeeds": []
}
```
