# 羊城晚报金羊网 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `ycwb`
- Namespace Name: `羊城晚报金羊网`
- Route Path: `/ycwb/:node`
- Route Name: `新闻`
- Example: `/ycwb/1`
- URL: `xwlb.com.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TimWu007`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
注：小部分栏目的 URL 会给出 nodeid。如未给出，可打开某条新闻链接后，查看网页源代码，搜索 nodeid 的值。

常用栏目节点：

| 首页 | 中国 | 国际 | 体育 | 要闻 | 珠江评论 | 民生观察 | 房产 | 金羊教育 | 金羊财富 | 金羊文化 | 金羊健康 | 金羊汽车 |
| ---- | ---- | ---- | ---- | ---- | -------- | -------- | ---- | -------- | -------- | -------- | -------- | -------- |
| 1    | 14   | 15   | 16   | 22   | 1875     | 21773    | 222  | 5725     | 633      | 5281     | 21692    | 223      |

| 广州 | 广州 - 广州要闻 | 广州 - 社会百态 | 广州 - 深读广州 | 广州 - 生活服务 | 今日大湾区 | 广东 - 政经热闻 | 广东 - 民生视点 | 广东 - 滚动新闻 |
| ---- | --------------- | --------------- | --------------- | --------------- | ---------- | --------------- | --------------- | --------------- |
| 18   | 5261            | 6030            | 13352           | 83422           | 100418     | 13074           | 12252           | 12212           |

## Parameters
- `node`: 栏目 id


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "注：小部分栏目的 URL 会给出 nodeid。如未给出，可打开某条新闻链接后，查看网页源代码，搜索 nodeid 的值。\n\n常用栏目节点：\n\n| 首页 | 中国 | 国际 | 体育 | 要闻 | 珠江评论 | 民生观察 | 房产 | 金羊教育 | 金羊财富 | 金羊文化 | 金羊健康 | 金羊汽车 |\n| ---- | ---- | ---- | ---- | ---- | -------- | -------- | ---- | -------- | -------- | -------- | -------- | -------- |\n| 1    | 14   | 15   | 16   | 22   | 1875     | 21773    | 222  | 5725     | 633      | 5281     | 21692    | 223      |\n\n| 广州 | 广州 - 广州要闻 | 广州 - 社会百态 | 广州 - 深读广州 | 广州 - 生活服务 | 今日大湾区 | 广东 - 政经热闻 | 广东 - 民生视点 | 广东 - 滚动新闻 |\n| ---- | --------------- | --------------- | --------------- | --------------- | ---------- | --------------- | --------------- | --------------- |\n| 18   | 5261            | 6030            | 13352           | 83422           | 100418     | 13074           | 12252           | 12212           |",
  "example": "/ycwb/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 32,
  "location": "index.tsx",
  "maintainers": [
    "TimWu007"
  ],
  "name": "新闻",
  "parameters": {
    "node": "栏目 id"
  },
  "path": "/:node",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "羊城晚报金羊网 - - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "54807548014042128",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ycwb.com/",
      "title": "羊城晚报金羊网 -",
      "type": "feed",
      "url": "rsshub://ycwb/5261"
    },
    {
      "description": "羊城晚报金羊网 - - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65552639683390464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ycwb.com/",
      "title": "羊城晚报金羊网 -",
      "type": "feed",
      "url": "rsshub://ycwb/1"
    }
  ]
}
```
