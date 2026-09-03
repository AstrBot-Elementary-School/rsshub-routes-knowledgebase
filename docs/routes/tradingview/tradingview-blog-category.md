# TradingView - Blog

## Coverage
`index-only`

## Route
- Namespace: `tradingview`
- Namespace Name: `TradingView`
- Route Path: `/tradingview/blog/:category{.+}?`
- Route Name: `Blog`
- Example: `/tradingview/blog/en`
- URL: `tradingview.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
#### Language

| Id | Language            |
| -- | ------------------- |
| en | English             |
| ru | Русский             |
| ja | 日本語              |
| es | Español             |
| tr | Türkçe              |
| ko | 한국어              |
| it | Italiano            |
| pt | Português do Brasil |
| de | Deutsch             |
| fr | Français            |
| pl | Polski              |
| id | Bahasa Indonesia    |
| my | Bahasa Malaysia     |
| tw | 繁體                |
| cn | 简体                |
| vi | Tiếng Việt          |
| th | ภาษาไทย             |
| sv | Svenska             |
| ar | العربية             |
| il | Hebrew              |

#### Category

| Category                                                                                       | ID                            |
| ---------------------------------------------------------------------------------------------- | ----------------------------- |
| [Alerts](https://www.tradingview.com/blog/en/category/alerts/)                                 | category/alerts               |
| [Bitcoin and Crypto](https://www.tradingview.com/blog/en/category/bitcoin-charts/)             | category/bitcoin-charts       |
| [Business Updates](https://www.tradingview.com/blog/en/category/business-updates/)             | category/business-updates     |
| [Charting](https://www.tradingview.com/blog/en/category/charts/)                               | category/charts               |
| [Charting Library](https://www.tradingview.com/blog/en/category/charting-library/)             | category/charting-library     |
| [Data Feeds and Exchanges](https://www.tradingview.com/blog/en/category/data-feeds-exchanges/) | category/data-feeds-exchanges |
| [Desktop](https://www.tradingview.com/blog/en/category/desktop/)                               | category/desktop              |
| [Market Analysis](https://www.tradingview.com/blog/en/category/market-analysis/)               | category/market-analysis      |
| [Mobile](https://www.tradingview.com/blog/en/category/mobile/)                                 | category/mobile               |
| [Pine Script®](https://www.tradingview.com/blog/en/category/pine/)                             | category/pine                 |
| [Screener](https://www.tradingview.com/blog/en/category/stock-screener/)                       | category/stock-screener       |
| [Social](https://www.tradingview.com/blog/en/category/social/)                                 | category/social               |
| [Trading and Brokerage](https://www.tradingview.com/blog/en/category/trading/)                 | category/trading              |
| [Widgets](https://www.tradingview.com/blog/en/category/widgets/)                               | category/widgets              |

## Parameters
- `category`: Language, see below, `en` as English by default


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "#### Language\n\n| Id | Language            |\n| -- | ------------------- |\n| en | English             |\n| ru | Русский             |\n| ja | 日本語              |\n| es | Español             |\n| tr | Türkçe              |\n| ko | 한국어              |\n| it | Italiano            |\n| pt | Português do Brasil |\n| de | Deutsch             |\n| fr | Français            |\n| pl | Polski              |\n| id | Bahasa Indonesia    |\n| my | Bahasa Malaysia     |\n| tw | 繁體                |\n| cn | 简体                |\n| vi | Tiếng Việt          |\n| th | ภาษาไทย             |\n| sv | Svenska             |\n| ar | العربية             |\n| il | Hebrew              |\n\n#### Category\n\n| Category                                                                                       | ID                            |\n| ---------------------------------------------------------------------------------------------- | ----------------------------- |\n| [Alerts](https://www.tradingview.com/blog/en/category/alerts/)                                 | category/alerts               |\n| [Bitcoin and Crypto](https://www.tradingview.com/blog/en/category/bitcoin-charts/)             | category/bitcoin-charts       |\n| [Business Updates](https://www.tradingview.com/blog/en/category/business-updates/)             | category/business-updates     |\n| [Charting](https://www.tradingview.com/blog/en/category/charts/)                               | category/charts               |\n| [Charting Library](https://www.tradingview.com/blog/en/category/charting-library/)             | category/charting-library     |\n| [Data Feeds and Exchanges](https://www.tradingview.com/blog/en/category/data-feeds-exchanges/) | category/data-feeds-exchanges |\n| [Desktop](https://www.tradingview.com/blog/en/category/desktop/)                               | category/desktop              |\n| [Market Analysis](https://www.tradingview.com/blog/en/category/market-analysis/)               | category/market-analysis      |\n| [Mobile](https://www.tradingview.com/blog/en/category/mobile/)                                 | category/mobile               |\n| [Pine Script®](https://www.tradingview.com/blog/en/category/pine/)                             | category/pine                 |\n| [Screener](https://www.tradingview.com/blog/en/category/stock-screener/)                       | category/stock-screener       |\n| [Social](https://www.tradingview.com/blog/en/category/social/)                                 | category/social               |\n| [Trading and Brokerage](https://www.tradingview.com/blog/en/category/trading/)                 | category/trading              |\n| [Widgets](https://www.tradingview.com/blog/en/category/widgets/)                               | category/widgets              |",
  "example": "/tradingview/blog/en",
  "heat": 5,
  "location": "blog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Blog",
  "parameters": {
    "category": "Language, see below, `en` as English by default"
  },
  "path": "/blog/:category{.+}?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "我们几乎每周都会发布新的更新。随时了解我们所有最新的公司新闻和观点。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69384991748864027",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.tradingview.com/blog/cn/",
      "title": "TradingView交易员博客 — 平台更新和新闻",
      "type": "feed",
      "url": "rsshub://tradingview/blog/cn"
    }
  ]
}
```
