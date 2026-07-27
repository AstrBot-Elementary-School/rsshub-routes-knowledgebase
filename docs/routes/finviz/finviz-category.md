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
  "heat": 340,
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
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
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
