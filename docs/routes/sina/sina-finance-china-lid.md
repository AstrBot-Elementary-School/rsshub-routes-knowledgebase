# 新浪 - 财经－国內

## Coverage
`index-only`

## Route
- Namespace: `sina`
- Namespace Name: `新浪`
- Route Path: `/sina/finance/china/:lid?`
- Route Name: `财经－国內`
- Example: `/sina/finance/china`
- URL: `finance.sina.com.cn/china`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `yubinbai`
- Source Location: `finance/china.ts`
- Source Module: `_None_`

## Description
| 国内滚动 | 宏观经济 | 金融新闻 | 地方经济 | 部委动态 | 今日财经 TOP10 |
| -------- | -------- | -------- | -------- | -------- | -------------- |
| 1686     | 1687     | 1690     | 1688     | 1689     | 3231           |

## Parameters
- `lid`: 分区 id，见下表，默认为 `1686`


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
  - `finance.sina.com.cn/china`
  - `finance.sina.com.cn/`
- `target`: `/finance/china`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 国内滚动 | 宏观经济 | 金融新闻 | 地方经济 | 部委动态 | 今日财经 TOP10 |\n| -------- | -------- | -------- | -------- | -------- | -------------- |\n| 1686     | 1687     | 1690     | 1688     | 1689     | 3231           |",
  "example": "/sina/finance/china",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 259,
  "location": "finance/china.ts",
  "maintainers": [
    "yubinbai"
  ],
  "name": "财经－国內",
  "parameters": {
    "lid": "分区 id，见下表，默认为 `1686`"
  },
  "path": "/finance/china/:lid?",
  "radar": [
    {
      "source": [
        "finance.sina.com.cn/china",
        "finance.sina.com.cn/"
      ],
      "target": "/finance/china"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "新浪财经－国内滚动 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64235783022956544",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://finance.sina.com.cn/china/",
      "title": "新浪财经－国内滚动",
      "type": "feed",
      "url": "rsshub://sina/finance/china"
    },
    {
      "description": "新浪财经－金融新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59799220289372188",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://finance.sina.com.cn/china/",
      "title": "新浪财经－金融新闻",
      "type": "feed",
      "url": "rsshub://sina/finance/china/1690"
    }
  ],
  "url": "finance.sina.com.cn/china"
}
```
