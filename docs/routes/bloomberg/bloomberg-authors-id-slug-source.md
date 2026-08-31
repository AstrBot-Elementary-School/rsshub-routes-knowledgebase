# Bloomberg - Authors

## Coverage
`index-only`

## Route
- Namespace: `bloomberg`
- Namespace Name: `Bloomberg`
- Route Path: `/bloomberg/authors/:id/:slug/:source?`
- Route Name: `Authors`
- Example: `/bloomberg/authors/ARbTQlRLRjE/matthew-s-levine`
- URL: `www.bloomberg.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `josh, pseudoyu`
- Source Location: `authors.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Author ID, can be found in URL
- `slug`: Author Slug, can be found in URL
- `source`: Data source, either `api` or `rss`,`api` by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.bloomberg.com/*/authors/:id/:slug`
  - `www.bloomberg.com/authors/:id/:slug`
- `target`: `/authors/:id/:slug`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/bloomberg/authors/ARbTQlRLRjE/matthew-s-levine",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 48,
  "location": "authors.ts",
  "maintainers": [
    "josh",
    "pseudoyu"
  ],
  "name": "Authors",
  "parameters": {
    "id": "Author ID, can be found in URL",
    "slug": "Author Slug, can be found in URL",
    "source": "Data source, either `api` or `rss`,`api` by default"
  },
  "path": "/authors/:id/:slug/:source?",
  "radar": [
    {
      "source": [
        "www.bloomberg.com/*/authors/:id/:slug",
        "www.bloomberg.com/authors/:id/:slug"
      ],
      "target": "/authors/:id/:slug"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Bloomberg - matthew-s-levine - Powered by RSSHub",
      "errorAt": "2025-02-04T02:35:57.482Z",
      "errorMessage": "[GET] \"https://www.bloomberg.com/lineup/api/lazy_load_author_stories?slug=ARbTQlRLRjE/matthew-s-levine&authorType=default&page=1\": 403 Forbidden\n",
      "id": "54713301214977024",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bloomberg.com/authors/ARbTQlRLRjE/matthew-s-levine",
      "title": "Bloomberg - matthew-s-levine",
      "type": "feed",
      "url": "rsshub://bloomberg/authors/ARbTQlRLRjE/matthew-s-levine"
    },
    {
      "description": "Bloomberg - mark-gurman - Powered by RSSHub",
      "errorAt": "2025-02-04T03:11:54.228Z",
      "errorMessage": "Failed to fetch\n[GET] \"https://www.bloomberg.com/lineup/api/lazy_load_author_stories?slug=AS7Hj1mBMGM/mark-gurman&authorType=default&page=1\": 403 Forbidden\n",
      "id": "69567457875551232",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bloomberg.com/authors/AS7Hj1mBMGM/mark-gurman",
      "title": "Bloomberg - mark-gurman",
      "type": "feed",
      "url": "rsshub://bloomberg/authors/AS7Hj1mBMGM/mark-gurman"
    }
  ],
  "view": 0
}
```
