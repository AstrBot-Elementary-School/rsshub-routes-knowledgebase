# DNA India - News

## Coverage
`index-only`

## Route
- Namespace: `dnaindia`
- Namespace Name: `DNA India`
- Route Path: `/dnaindia/:category`
- Route Name: `News`
- Example: `/dnaindia/headlines`
- URL: `www.dnaindia.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `Rjnishant530`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
Categories:

| Headlines | Explainer | India | Entertainment | Sports | Viral | Lifestyle | Education | Business | World |
| --------- | --------- | ----- | ------------- | ------ | ----- | --------- | --------- | -------- | ----- |
| headlines | explainer | india | entertainment | sports | viral | lifestyle | education | business | world |

## Parameters
- `category`: Find it in the URL, or tables below


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.dnaindia.com/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Categories:\n\n| Headlines | Explainer | India | Entertainment | Sports | Viral | Lifestyle | Education | Business | World |\n| --------- | --------- | ----- | ------------- | ------ | ----- | --------- | --------- | -------- | ----- |\n| headlines | explainer | india | entertainment | sports | viral | lifestyle | education | business | world |",
  "example": "/dnaindia/headlines",
  "heat": 6,
  "location": "news.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "News",
  "parameters": {
    "category": "Find it in the URL, or tables below"
  },
  "path": "/:category",
  "radar": [
    {
      "source": [
        "www.dnaindia.com/:category"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Latest News on dnaIndia.com - Powered by RSSHub",
      "errorAt": "2026-05-02T17:34:20.142Z",
      "errorMessage": "Failed to fetch\n",
      "id": "62339610691806208",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dnaindia.com/headlines",
      "title": "DNA India",
      "type": "feed",
      "url": "rsshub://dnaindia/headlines"
    },
    {
      "description": null,
      "errorAt": "2025-06-29T08:29:37.667Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "162063218996792351",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://dnaindia/india"
    }
  ],
  "url": "www.dnaindia.com"
}
```
