# finviz - News

## Coverage
`index-only`

## Route
- Namespace: `finviz`
- Namespace Name: `finviz`
- Route Path: `/finviz/:category?`
- Route Name: `News`
- Example: `/finviz`
- URL: `finviz.com/news.ashx`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| News | Blogs |
| ---- | ----- |
| news | blogs |

## Parameters
- `category`: {"description": "Category, see below, News by default", "options": [{"label": "news", "value": "news"}, {"label": "blogs", "value": "blogs"}]}


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
  - `finviz.com/news.ashx`
  - `finviz.com/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| News | Blogs |\n| ---- | ----- |\n| news | blogs |",
  "example": "/finviz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 341,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News",
  "parameters": {
    "category": {
      "description": "Category, see below, News by default",
      "options": [
        {
          "label": "news",
          "value": "news"
        },
        {
          "label": "blogs",
          "value": "blogs"
        }
      ]
    }
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "finviz.com/news.ashx",
        "finviz.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Stock screener for investors and traders, financial visualizations. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72642794272886784",
      "image": "https://finviz.com/img/logo.svg#free",
      "ownerUserId": null,
      "siteUrl": "https://finviz.com/news.ashx",
      "title": "finviz - news",
      "type": "feed",
      "url": "rsshub://finviz/news"
    },
    {
      "description": "Stock screener for investors and traders, financial visualizations. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59063423343404032",
      "image": "https://finviz.com/img/logo.svg#free",
      "ownerUserId": null,
      "siteUrl": "https://finviz.com/news.ashx",
      "title": "finviz - News",
      "type": "feed",
      "url": "rsshub://finviz"
    }
  ],
  "url": "finviz.com/news.ashx",
  "view": 0
}
```
