# La Jornada - News

## Coverage
`index-only`

## Route
- Namespace: `jornada`
- Namespace Name: `La Jornada`
- Route Path: `/jornada/:date?/:category?`
- Route Name: `News`
- Example: `/jornada/2022-10-12/capital`
- URL: `jornada.com.mx`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `Thealf154`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Provides a way to get an specific rss feed by date and category over the official one.

| Category             | `:category` |
| -------------------- | ----------- |
| Capital              | capital     |
| Cartones             | cartones    |
| Ciencia y Tecnología | ciencia     |
| Cultura              | cultura     |
| Deportes             | deportes    |
| Economía             | economia    |
| Estados              | estados     |
| Mundo                | mundo       |
| Opinión              | opinion     |
| Política             | politica    |
| Sociedad             | sociedad    |

## Parameters
- `date`: Date string, must be in format of `YYYY-MM-DD`. You can get today's news using `today`
- `category`: Category, refer to the table below


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Provides a way to get an specific rss feed by date and category over the official one.\n\n| Category             | `:category` |\n| -------------------- | ----------- |\n| Capital              | capital     |\n| Cartones             | cartones    |\n| Ciencia y Tecnología | ciencia     |\n| Cultura              | cultura     |\n| Deportes             | deportes    |\n| Economía             | economia    |\n| Estados              | estados     |\n| Mundo                | mundo       |\n| Opinión              | opinion     |\n| Política             | politica    |\n| Sociedad             | sociedad    |",
  "example": "/jornada/2022-10-12/capital",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "Thealf154"
  ],
  "name": "News",
  "parameters": {
    "category": "Category, refer to the table below",
    "date": "Date string, must be in format of `YYYY-MM-DD`. You can get today's news using `today`"
  },
  "path": "/:date?/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
