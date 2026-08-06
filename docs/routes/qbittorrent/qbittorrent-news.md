# qBittorrent - News

## Coverage
`index-only`

## Route
- Namespace: `qbittorrent`
- Namespace Name: `qBittorrent`
- Route Path: `/qbittorrent/news`
- Route Name: `News`
- Example: `/qbittorrent/news`
- URL: `qbittorrent.org/news.php`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

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
  - `qbittorrent.org/news.php`
  - `qbittorrent.org/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/qbittorrent/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 16,
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "qbittorrent.org/news.php",
        "qbittorrent.org/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "qBittorrent News - Powered by RSSHub",
      "errorAt": "2025-07-01T19:06:28.681Z",
      "errorMessage": "[GET] \"https://www.qbittorrent.org/news.php\": 403 Forbidden\n[GET] \"https://www.qbittorrent.org/news.php\": 403 Forbidden\n",
      "id": "43121778624967680",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.qbittorrent.org/news.php",
      "title": "qBittorrent News",
      "type": "feed",
      "url": "rsshub://qbittorrent/news"
    }
  ],
  "url": "qbittorrent.org/news.php"
}
```
