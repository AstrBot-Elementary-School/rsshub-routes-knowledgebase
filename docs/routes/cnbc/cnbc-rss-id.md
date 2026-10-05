# CNBC - Full article RSS

## Coverage
`index-only`

## Route
- Namespace: `cnbc`
- Namespace Name: `CNBC`
- Route Path: `/cnbc/rss/:id?`
- Route Name: `Full article RSS`
- Example: `/cnbc/rss`
- URL: `search.cnbc.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `rss.ts`
- Source Module: `_None_`

## Description
Provides a better reading experience (full articles) over the official ones.

Support all channels, refer to [CNBC RSS feeds](https://www.cnbc.com/rss-feeds/).

## Parameters
- `id`: Channel ID, can be found in Official RSS URL, `100003114` (Top News) by default


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
  - `www.cnbc.com/id/:id/device/rss/rss.html`
- `target`: `/rss/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Provides a better reading experience (full articles) over the official ones.\n\nSupport all channels, refer to [CNBC RSS feeds](https://www.cnbc.com/rss-feeds/).",
  "example": "/cnbc/rss",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 341,
  "location": "rss.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Full article RSS",
  "parameters": {
    "id": "Channel ID, can be found in Official RSS URL, `100003114` (Top News) by default"
  },
  "path": "/rss/:id?",
  "radar": [
    {
      "source": [
        "www.cnbc.com/id/:id/device/rss/rss.html"
      ],
      "target": "/rss/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "CNBC is the world leader in business news and real-time financial market coverage. Find fast, actionable information. - Powered by RSSHub",
      "errorAt": "2026-10-04T13:11:09.034Z",
      "errorMessage": "[GET] \"https://www.cnbc.com/2026/10/04//ai-wearables-oura-ipo-privacy.html\": 404 \n[GET] \"https://www.cnbc.com/2026/10/04//ai-wearables-oura-ipo-privacy.html\": 404 Not Found\n",
      "id": "59846974115348480",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cnbc.com/us-top-news-and-analysis/",
      "title": "US Top News and Analysis",
      "type": "feed",
      "url": "rsshub://cnbc/rss"
    },
    {
      "description": "CNBC is the world leader in business news and real-time financial market coverage. Find fast, actionable information. - Powered by RSSHub",
      "errorAt": "2026-10-04T12:57:17.479Z",
      "errorMessage": "[GET] \"https://www.cnbc.com/2026/10/04//ai-wearables-oura-ipo-privacy.html\": 404 Not Found\n",
      "id": "77157605247889408",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cnbc.com/us-top-news-and-analysis/",
      "title": "US Top News and Analysis",
      "type": "feed",
      "url": "rsshub://cnbc/rss/100003114"
    }
  ]
}
```
