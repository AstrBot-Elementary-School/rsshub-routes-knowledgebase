# 乌拉邦 - 频道

## Coverage
`index-only`

## Route
- Namespace: `ulapia`
- Namespace Name: `乌拉邦`
- Route Path: `/ulapia/reports/:category?`
- Route Name: `频道`
- Example: `/ulapia/reports/stock_research`
- URL: `www.ulapia.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
|     个股研报    |      行业研报      |      策略研报      |     宏观研报    |    新股研报   | 券商晨报（今日晨报） |
| :-------------: | :----------------: | :----------------: | :-------------: | :-----------: | :------------------: |
| stock\_research | industry\_research | strategy\_research | macro\_research | ipo\_research |    brokerage\_news   |

## Parameters
- `category`: 频道类型，默认为券商晨报（今日晨报）


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
    "finance"
  ],
  "description": "|     个股研报    |      行业研报      |      策略研报      |     宏观研报    |    新股研报   | 券商晨报（今日晨报） |\n| :-------------: | :----------------: | :----------------: | :-------------: | :-----------: | :------------------: |\n| stock\\_research | industry\\_research | strategy\\_research | macro\\_research | ipo\\_research |    brokerage\\_news   |",
  "example": "/ulapia/reports/stock_research",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 133,
  "location": "index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "频道",
  "parameters": {
    "category": "频道类型，默认为券商晨报（今日晨报）"
  },
  "path": "/reports/:category?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "ulapia - 宏观研报 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60865831498850371",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.ulapia.com/reports/macro_research",
      "title": "ulapia - 宏观研报",
      "type": "feed",
      "url": "rsshub://ulapia/reports/macro_research"
    },
    {
      "description": "ulapia - 策略研报 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60865831498850372",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.ulapia.com/reports/strategy_research",
      "title": "ulapia - 策略研报",
      "type": "feed",
      "url": "rsshub://ulapia/reports/strategy_research"
    }
  ]
}
```
