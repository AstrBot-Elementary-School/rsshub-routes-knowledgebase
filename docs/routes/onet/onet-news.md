# Onet - News

## Coverage
`index-only`

## Route
- Namespace: `onet`
- Namespace Name: `Onet`
- Route Path: `/onet/news`
- Route Name: `News`
- Example: `/onet/news`
- URL: `wiadomosci.onet.pl/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Vegann`
- Source Location: `news.tsx`
- Source Module: `_None_`

## Description
This route provides a better reading experience (full text articles) over the official one for `https://wiadomosci.onet.pl`.

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
  - `wiadomosci.onet.pl/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "This route provides a better reading experience (full text articles) over the official one for `https://wiadomosci.onet.pl`.",
  "example": "/onet/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "news.tsx",
  "maintainers": [
    "Vegann"
  ],
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "wiadomosci.onet.pl/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Wiadomości wiadomosci.onet.pl - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73539947766496256",
      "image": "https://ocdn.eu/wiadomosciucs/static/logo2017/onet2017big_dark.png",
      "ownerUserId": null,
      "siteUrl": "https://wiadomosci.onet.pl/",
      "title": "Wiadomości wiadomosci.onet.pl",
      "type": "feed",
      "url": "rsshub://onet/news"
    }
  ],
  "url": "wiadomosci.onet.pl/"
}
```
