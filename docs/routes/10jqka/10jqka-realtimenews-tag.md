# 同花顺财经 - 7×24小时要闻直播

## Coverage
`index-only`

## Route
- Namespace: `10jqka`
- Namespace Name: `同花顺财经`
- Route Path: `/10jqka/realtimenews/:tag?`
- Route Name: `7×24小时要闻直播`
- Example: `/10jqka/realtimenews`
- URL: `news.10jqka.com.cn`
- Language: `_None_`
- Categories: `finance, popular`
- Maintainers: `nczitzk`
- Source Location: `realtimenews.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [7×24 小时要闻直播](https://news.10jqka.com.cn/realtimenews.html) 的 `公告` 标签。将 `公告` 作为标签参数填入，此时路由为 [`/10jqka/realtimenews/公告`](https://rsshub.app/10jqka/realtimenews/公告)。

若订阅 [7×24 小时要闻直播](https://news.10jqka.com.cn/realtimenews.html) 的 `公告` 和 `A股` 标签。将 `公告,A股` 作为标签参数填入，此时路由为 [`/10jqka/realtimenews/公告,A股`](https://rsshub.app/10jqka/realtimenews/公告,A股)。
:::

| 全部 | 重要 | A 股 | 港股 | 美股 | 机会 | 异动 | 公告 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |

## Parameters
- `tag`: 标签，默认为全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `title`: `全部`
- `source`:
  - `news.10jqka.com.cn/realtimenews.html`
- `target`: `/realtimenews/全部`
### Rule 2
- `title`: `重要`
- `source`:
  - `news.10jqka.com.cn/realtimenews.html`
- `target`: `/realtimenews/重要`
### Rule 3
- `title`: `A股`
- `source`:
  - `news.10jqka.com.cn/realtimenews.html`
- `target`: `/realtimenews/A股`
### Rule 4
- `title`: `港股`
- `source`:
  - `news.10jqka.com.cn/realtimenews.html`
- `target`: `/realtimenews/港股`
### Rule 5
- `title`: `美股`
- `source`:
  - `news.10jqka.com.cn/realtimenews.html`
- `target`: `/realtimenews/美股`
### Rule 6
- `title`: `机会`
- `source`:
  - `news.10jqka.com.cn/realtimenews.html`
- `target`: `/realtimenews/机会`
### Rule 7
- `title`: `异动`
- `source`:
  - `news.10jqka.com.cn/realtimenews.html`
- `target`: `/realtimenews/异动`
### Rule 8
- `title`: `公告`
- `source`:
  - `news.10jqka.com.cn/realtimenews.html`
- `target`: `/realtimenews/公告`

## Raw JSON
```json
{
  "categories": [
    "finance",
    "popular"
  ],
  "description": "::: tip\n若订阅 [7×24 小时要闻直播](https://news.10jqka.com.cn/realtimenews.html) 的 `公告` 标签。将 `公告` 作为标签参数填入，此时路由为 [`/10jqka/realtimenews/公告`](https://rsshub.app/10jqka/realtimenews/公告)。\n\n若订阅 [7×24 小时要闻直播](https://news.10jqka.com.cn/realtimenews.html) 的 `公告` 和 `A股` 标签。将 `公告,A股` 作为标签参数填入，此时路由为 [`/10jqka/realtimenews/公告,A股`](https://rsshub.app/10jqka/realtimenews/公告,A股)。\n:::\n\n| 全部 | 重要 | A 股 | 港股 | 美股 | 机会 | 异动 | 公告 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |",
  "example": "/10jqka/realtimenews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 1678,
  "location": "realtimenews.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "7×24小时要闻直播",
  "parameters": {
    "tag": "标签，默认为全部"
  },
  "path": "/realtimenews/:tag?",
  "radar": [
    {
      "source": [
        "news.10jqka.com.cn/realtimenews.html"
      ],
      "target": "/realtimenews/全部",
      "title": "全部"
    },
    {
      "source": [
        "news.10jqka.com.cn/realtimenews.html"
      ],
      "target": "/realtimenews/重要",
      "title": "重要"
    },
    {
      "source": [
        "news.10jqka.com.cn/realtimenews.html"
      ],
      "target": "/realtimenews/A股",
      "title": "A股"
    },
    {
      "source": [
        "news.10jqka.com.cn/realtimenews.html"
      ],
      "target": "/realtimenews/港股",
      "title": "港股"
    },
    {
      "source": [
        "news.10jqka.com.cn/realtimenews.html"
      ],
      "target": "/realtimenews/美股",
      "title": "美股"
    },
    {
      "source": [
        "news.10jqka.com.cn/realtimenews.html"
      ],
      "target": "/realtimenews/机会",
      "title": "机会"
    },
    {
      "source": [
        "news.10jqka.com.cn/realtimenews.html"
      ],
      "target": "/realtimenews/异动",
      "title": "异动"
    },
    {
      "source": [
        "news.10jqka.com.cn/realtimenews.html"
      ],
      "target": "/realtimenews/公告",
      "title": "公告"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "同花顺财经 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72098833744560128",
      "image": "http://i.thsi.cn/images/thscj/THSLogo.png",
      "ownerUserId": null,
      "siteUrl": "https://news.10jqka.com.cn/realtimenews.html",
      "title": "7*24小时全球财经直播_同花顺财经",
      "type": "feed",
      "url": "rsshub://10jqka/realtimenews"
    },
    {
      "description": "同花顺财经 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72148510666881024",
      "image": "http://i.thsi.cn/images/thscj/THSLogo.png",
      "ownerUserId": null,
      "siteUrl": "https://news.10jqka.com.cn/realtimenews.html",
      "title": "7*24小时全球财经直播_同花顺财经",
      "type": "feed",
      "url": "rsshub://10jqka/realtimenews/%E5%85%A8%E9%83%A8"
    }
  ],
  "url": "news.10jqka.com.cn"
}
```
