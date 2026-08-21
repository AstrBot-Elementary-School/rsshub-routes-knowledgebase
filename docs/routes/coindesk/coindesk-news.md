# CoinDesk - News

## Coverage
`index-only`

## Route
- Namespace: `coindesk`
- Namespace Name: `CoinDesk`
- Route Path: `/coindesk/news`
- Route Name: `News`
- Example: `/coindesk/news`
- URL: `coindesk.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `pseudoyu`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
Get latest news from CoinDesk with full text.

## Parameters
_None_


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
  - `coindesk.com/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Get latest news from CoinDesk with full text.",
  "example": "/coindesk/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 91,
  "location": "news.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "coindesk.com/"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Leader in cryptocurrency, Bitcoin, Ethereum, XRP, blockchain, DeFi, digital finance and Web 3.0 news with analysis, video and live price updates. - Powered by RSSHub",
      "errorAt": "2026-08-17T18:29:32.646Z",
      "errorMessage": "[GET] \"https://www.coindesk.com/markets/2026/08/18/kraken-adds-u-s-stocks-in-europe-as-tradfi-crypto-divide-blurs\": 429 Too Many Requests\n[GET] \"https://www.coindesk.com/markets/2026/08/18/kraken-adds-u-s-stocks-in-europe-as-tradfi-crypto-divide-blurs\": 429 Too Many Requests\n",
      "id": "126922928969806848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.coindesk.com/",
      "title": "CoinDesk: Bitcoin, Ethereum, Crypto News and Price Data",
      "type": "feed",
      "url": "rsshub://coindesk/news"
    }
  ]
}
```
