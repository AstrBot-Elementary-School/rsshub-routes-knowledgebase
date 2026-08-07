# 新浪 - 财经－滚动新闻

## Coverage
`index-only`

## Route
- Namespace: `sina`
- Namespace Name: `新浪`
- Route Path: `/sina/finance/rollnews/:lid?`
- Route Name: `财经－滚动新闻`
- Example: `/sina/finance/rollnews`
- URL: `finance.sina.com.cn/roll`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `betterandbetterii`
- Source Location: `finance/rollnews.ts`
- Source Module: `_None_`

## Description
| 财经 | 股市 | 美股 | 中国概念股 | 港股 | 研究报告 | 全球市场 | 外汇 |
| ---- | ---- | ---- | ---------- | ---- | -------- | -------- | ---- |
| 2519 | 2671 | 2672 | 2673       | 2674 | 2675     | 2676     | 2487 |

## Parameters
- `lid`: 分区 id，见下表，默认为 `2519`


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
  - `finance.sina.com.cn/roll`
  - `finance.sina.com.cn/`
- `target`: `/finance/rollnews`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 财经 | 股市 | 美股 | 中国概念股 | 港股 | 研究报告 | 全球市场 | 外汇 |\n| ---- | ---- | ---- | ---------- | ---- | -------- | -------- | ---- |\n| 2519 | 2671 | 2672 | 2673       | 2674 | 2675     | 2676     | 2487 |",
  "example": "/sina/finance/rollnews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "finance/rollnews.ts",
  "maintainers": [
    "betterandbetterii"
  ],
  "name": "财经－滚动新闻",
  "parameters": {
    "lid": "分区 id，见下表，默认为 `2519`"
  },
  "path": "/finance/rollnews/:lid?",
  "radar": [
    {
      "source": [
        "finance.sina.com.cn/roll",
        "finance.sina.com.cn/"
      ],
      "target": "/finance/rollnews"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "新浪财经－财经滚动新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "245850080340167680",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://finance.sina.com.cn/roll/#pageid=384&lid=2519&k=&num=50&page=1",
      "title": "新浪财经－财经滚动新闻",
      "type": "feed",
      "url": "rsshub://sina/finance/rollnews"
    }
  ],
  "url": "finance.sina.com.cn/roll"
}
```
