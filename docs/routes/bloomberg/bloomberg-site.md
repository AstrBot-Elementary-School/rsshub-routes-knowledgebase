# Bloomberg - Bloomberg Site

## Coverage
`index-only`

## Route
- Namespace: `bloomberg`
- Namespace Name: `Bloomberg`
- Route Path: `/bloomberg/:site?`
- Route Name: `Bloomberg Site`
- Example: `/bloomberg/bbiz`
- URL: `www.bloomberg.com`
- Language: `_None_`
- Categories: `finance, popular`
- Maintainers: `bigfei`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| Site ID      | Title        |
| ------------ | ------------ |
| /            | News         |
| bpol         | Politics     |
| bbiz         | Business     |
| markets      | Markets      |
| technology   | Technology   |
| green        | Green        |
| wealth       | Wealth       |
| pursuits     | Pursuits     |
| bview        | Opinion      |
| equality     | Equality     |
| businessweek | Businessweek |
| citylab      | CityLab      |

## Parameters
- `site`: {"description": "Site ID, can be found below", "options": [{"label": "News", "value": "/"}, {"label": "Politics", "value": "bpol"}, {"label": "Business", "value": "bbiz"}, {"label": "Markets", "value": "markets"}, {"label": "Technology", "value": "technology"}, {"label": "Green", "value": "green"}, {"label": "Wealth", "value": "wealth"}, {"label": "Pursuits", "value": "pursuits"}, {"label": "Opinion", "value": "bview"}, {"label": "Equality", "value": "equality"}, {"label": "Businessweek", "value": "businessweek"}, {"label": "CityLab", "value": "citylab"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "finance",
    "popular"
  ],
  "description": "| Site ID      | Title        |\n| ------------ | ------------ |\n| /            | News         |\n| bpol         | Politics     |\n| bbiz         | Business     |\n| markets      | Markets      |\n| technology   | Technology   |\n| green        | Green        |\n| wealth       | Wealth       |\n| pursuits     | Pursuits     |\n| bview        | Opinion      |\n| equality     | Equality     |\n| businessweek | Businessweek |\n| citylab      | CityLab      |",
  "example": "/bloomberg/bbiz",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5523,
  "location": "index.ts",
  "maintainers": [
    "bigfei"
  ],
  "name": "Bloomberg Site",
  "parameters": {
    "site": {
      "description": "Site ID, can be found below",
      "options": [
        {
          "label": "News",
          "value": "/"
        },
        {
          "label": "Politics",
          "value": "bpol"
        },
        {
          "label": "Business",
          "value": "bbiz"
        },
        {
          "label": "Markets",
          "value": "markets"
        },
        {
          "label": "Technology",
          "value": "technology"
        },
        {
          "label": "Green",
          "value": "green"
        },
        {
          "label": "Wealth",
          "value": "wealth"
        },
        {
          "label": "Pursuits",
          "value": "pursuits"
        },
        {
          "label": "Opinion",
          "value": "bview"
        },
        {
          "label": "Equality",
          "value": "equality"
        },
        {
          "label": "Businessweek",
          "value": "businessweek"
        },
        {
          "label": "CityLab",
          "value": "citylab"
        }
      ]
    }
  },
  "path": "/:site?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Bloomberg - News - Powered by RSSHub",
      "errorAt": "2026-07-15T12:52:21.257Z",
      "errorMessage": "[GET] \"https://www.bloomberg.com/feeds///sitemap_news.xml\": 404 Not Found\n[GET] \"https://www.bloomberg.com/feeds///sitemap_news.xml\": 404 \n[GET] \"https://www.bloomberg.com/feeds///sitemap_news.xml\": 404 Not Found\nAuthentication failed. Access denied.\n/bloomberg/%2F\n[GET] \"https://www.bloomberg.com/feeds///sitemap_news.xml\": <no response> fetch failed\n502 \n[GET] \"https://www.bloomberg.com/feeds///sitemap_news.xml\": 404 Not Found\n[GET] \"https://www.bloomberg.com/feeds///sitemap_news.xml\": 404 Not Found\n",
      "id": "72541421314282496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bloomberg.com/feeds///sitemap_news.xml",
      "title": "Bloomberg - News",
      "type": "feed",
      "url": "rsshub://bloomberg/%2F"
    },
    {
      "description": "Bloomberg - News - Powered by RSSHub",
      "errorAt": "2026-07-17T08:12:23.276Z",
      "errorMessage": "[GET] \"https://www.bloomberg.com/feeds/sitemap_news.xml\": 404 Not Found\n[GET] \"https://www.bloomberg.com/feeds/sitemap_news.xml\": 404 Not Found\nAuthentication failed. Access denied.\n/bloomberg\n[GET] \"https://www.bloomberg.com/feeds/sitemap_news.xml\": 404 Not Found\n[GET] \"https://www.bloomberg.com/feeds/sitemap_news.xml\": 404 Not Found\n[GET] \"https://www.bloomberg.com/feeds/sitemap_news.xml\": 404 Not Found\n[GET] \"https://www.bloomberg.com/feeds/sitemap_news.xml\": 404 Not Found\n[GET] \"https://www.bloomberg.com/feeds/sitemap_news.xml\": 404 Not Found\n[GET] \"https://www.bloomberg.com/feeds/sitemap_news.xml\": 404 Not Found\n",
      "id": "64731996464440320",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bloomberg.com/feeds/sitemap_news.xml",
      "title": "Bloomberg - News",
      "type": "feed",
      "url": "rsshub://bloomberg"
    }
  ],
  "view": 0
}
```
