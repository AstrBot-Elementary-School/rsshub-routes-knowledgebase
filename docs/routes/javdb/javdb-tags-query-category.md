# JavDB - 分類

## Coverage
`index-only`

## Route
- Namespace: `javdb`
- Namespace Name: `JavDB`
- Route Path: `/javdb/tags/:query?/:category?`
- Route Name: `分類`
- Example: `/javdb/tags/c2=5&c10=1`
- URL: `javdb.com/`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `tags.ts`
- Source Module: `_None_`

## Description
::: tip
在 [分類](https://javdb.com/tags) 中选定分类后，URL 中 `tags?` 后的字段即为筛选参数。

如 `https://javdb.com/tags?c2=5&c10=1` 中 `c2=5&c10=1` 为筛选参数。
:::

分类

| 有碼     | 無碼       | 歐美    |
| -------- | ---------- | ------- |
| censored | uncensored | western |

## Parameters
- `query`: 筛选，默认为 `c10=1`
- `category`: 分类，见下表，默认为 `有碼`


## Features
- `requireConfig`: [{"description": "JavDB登陆后的session值，可在控制台的cookie下查找 `_jdb_session` 的值，即可获取", "name": "JAVDB_SESSION", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `javdb.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\n在 [分類](https://javdb.com/tags) 中选定分类后，URL 中 `tags?` 后的字段即为筛选参数。\n\n如 `https://javdb.com/tags?c2=5&c10=1` 中 `c2=5&c10=1` 为筛选参数。\n:::\n\n分类\n\n| 有碼     | 無碼       | 歐美    |\n| -------- | ---------- | ------- |\n| censored | uncensored | western |",
  "example": "/javdb/tags/c2=5&c10=1",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "JavDB登陆后的session值，可在控制台的cookie下查找 `_jdb_session` 的值，即可获取",
        "name": "JAVDB_SESSION",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "tags.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分類",
  "parameters": {
    "category": "分类，见下表，默认为 `有碼`",
    "query": "筛选，默认为 `c10=1`"
  },
  "path": "/tags/:query?/:category?",
  "radar": [
    {
      "source": [
        "javdb.com/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-05-23T18:45:47.319Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "148757739569766447",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://javdb/tags/c2=5&c10=1"
    }
  ],
  "url": "javdb.com/"
}
```
