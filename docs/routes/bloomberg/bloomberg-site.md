# Bloomberg - Bloomberg Site

## Coverage
`index-only`

## Route
- Namespace: `bloomberg`
- Namespace Name: `Bloomberg`
- Route Path: `/bloomberg/:site?`
- Route Name: `Bloomberg Site`
- Example: `/bloomberg/business`
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
| politics     | Politics     |
| business     | Business     |
| markets      | Markets      |
| technology   | Technology   |
| wealth       | Wealth       |
| bview        | Opinion      |
| businessweek | Businessweek |
| economics    | Economics    |
| industries   | Industries   |
| crypto       | Crypto       |

Legacy site IDs `bpol` and `bbiz` still work as aliases of `politics` and `business`.

## Parameters
- `site`: {"description": "Site ID, can be found below", "options": [{"label": "News", "value": "/"}, {"label": "Politics", "value": "politics"}, {"label": "Business", "value": "business"}, {"label": "Markets", "value": "markets"}, {"label": "Technology", "value": "technology"}, {"label": "Wealth", "value": "wealth"}, {"label": "Opinion", "value": "bview"}, {"label": "Businessweek", "value": "businessweek"}, {"label": "Economics", "value": "economics"}, {"label": "Industries", "value": "industries"}, {"label": "Crypto", "value": "crypto"}]}


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
  "description": "| Site ID      | Title        |\n| ------------ | ------------ |\n| /            | News         |\n| politics     | Politics     |\n| business     | Business     |\n| markets      | Markets      |\n| technology   | Technology   |\n| wealth       | Wealth       |\n| bview        | Opinion      |\n| businessweek | Businessweek |\n| economics    | Economics    |\n| industries   | Industries   |\n| crypto       | Crypto       |\n\nLegacy site IDs `bpol` and `bbiz` still work as aliases of `politics` and `business`.",
  "example": "/bloomberg/business",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5558,
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
          "value": "politics"
        },
        {
          "label": "Business",
          "value": "business"
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
          "label": "Wealth",
          "value": "wealth"
        },
        {
          "label": "Opinion",
          "value": "bview"
        },
        {
          "label": "Businessweek",
          "value": "businessweek"
        },
        {
          "label": "Economics",
          "value": "economics"
        },
        {
          "label": "Industries",
          "value": "industries"
        },
        {
          "label": "Crypto",
          "value": "crypto"
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
      "errorAt": null,
      "errorMessage": null,
      "id": "72541421314282496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.bloomberg.com/",
      "title": "Bloomberg - News",
      "type": "feed",
      "url": "rsshub://bloomberg/%2F"
    },
    {
      "description": "Bloomberg - News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64731996464440320",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.bloomberg.com/",
      "title": "Bloomberg - News",
      "type": "feed",
      "url": "rsshub://bloomberg"
    }
  ],
  "view": 0
}
```
