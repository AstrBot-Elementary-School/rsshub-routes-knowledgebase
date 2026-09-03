# The White House - News

## Coverage
`index-only`

## Route
- Namespace: `whitehouse`
- Namespace Name: `The White House`
- Route Path: `/whitehouse/news/:category?`
- Route Name: `News`
- Example: `/whitehouse/news`
- URL: `whitehouse.gov`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk, hkamran80`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| All | Articles | Briefings and Statements | Presidential Actions | Remarks |
| --- | -------- | ------------------------ | -------------------- | ------- |
|     | articles | briefings-statements     | presidential-actions | remarks |

## Parameters
- `category`: Category, see below, all by default


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
  - `whitehouse.gov/:category`
  - `whitehouse.gov/`
- `target`: `/news/:category`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| All | Articles | Briefings and Statements | Presidential Actions | Remarks |\n| --- | -------- | ------------------------ | -------------------- | ------- |\n|     | articles | briefings-statements     | presidential-actions | remarks |",
  "example": "/whitehouse/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 77,
  "location": "news.ts",
  "maintainers": [
    "nczitzk",
    "hkamran80"
  ],
  "name": "News",
  "parameters": {
    "category": "Category, see below, all by default"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "whitehouse.gov/:category",
        "whitehouse.gov/"
      ],
      "target": "/news/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "News – The White House - Powered by RSSHub",
      "errorAt": "2026-09-02T07:13:21.389Z",
      "errorMessage": "Failed to fetch\n530 \nFailed to fetch\n",
      "id": "105673440807055360",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.whitehouse.gov/news/",
      "title": "News – The White House",
      "type": "feed",
      "url": "rsshub://whitehouse/news"
    },
    {
      "description": "Presidential Actions – The White House - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "121830281207047168",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.whitehouse.gov/presidential-actions/",
      "title": "Presidential Actions – The White House",
      "type": "feed",
      "url": "rsshub://whitehouse/news/presidential-actions"
    }
  ]
}
```
