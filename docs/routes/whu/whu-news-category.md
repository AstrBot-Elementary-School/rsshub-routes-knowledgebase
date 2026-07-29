# 武汉大学 - 新闻网

## Coverage
`index-only`

## Route
- Namespace: `whu`
- Namespace Name: `武汉大学`
- Route Path: `/whu/news/:category{.+}?`
- Route Name: `新闻网`
- Example: `/whu/news`
- URL: `cs.whu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `SChen1024, nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
category 参数可选，范围如下:

| 新闻栏目 | 武大资讯         | 学术动态    | 珞珈影像         | 武大视频         |
| -------- | ---------------- | ----------- | ---------------- | ---------------- |
| 参数     | 0 或 `wdzx/wdyw` | 1 或 `kydt` | 2 或 `stkj/ljyx` | 3 或 `stkj/wdsp` |

此外 route 后可以加上 `?limit=n` 的查询参数，表示只获取前 n 条新闻；如果不指定默认为 10。

## Parameters
- `category`: 分类，见下表，默认为 `wdzx/wdyw`， 即 **武大要闻**


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "category 参数可选，范围如下:\n\n| 新闻栏目 | 武大资讯         | 学术动态    | 珞珈影像         | 武大视频         |\n| -------- | ---------------- | ----------- | ---------------- | ---------------- |\n| 参数     | 0 或 `wdzx/wdyw` | 1 或 `kydt` | 2 或 `stkj/ljyx` | 3 或 `stkj/wdsp` |\n\n此外 route 后可以加上 `?limit=n` 的查询参数，表示只获取前 n 条新闻；如果不指定默认为 10。",
  "example": "/whu/news",
  "heat": 4,
  "location": "news.ts",
  "maintainers": [
    "SChen1024",
    "nczitzk"
  ],
  "name": "新闻网",
  "parameters": {
    "category": "分类，见下表，默认为 `wdzx/wdyw`， 即 **武大要闻**"
  },
  "path": "/news/:category{.+}?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "武汉大学新闻网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59556206825577472",
      "image": "https://news.whu.edu.cn/images/logoa.png",
      "ownerUserId": null,
      "siteUrl": "https://news.whu.edu.cn/wdzx/wdyw.htm",
      "title": "武汉大学新闻网 - 武大要闻",
      "type": "feed",
      "url": "rsshub://whu/news"
    }
  ]
}
```
