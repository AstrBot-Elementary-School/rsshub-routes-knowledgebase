# RTHK 香港電台 - News

## Coverage
`index-only`

## Route
- Namespace: `rthk`
- Namespace Name: `RTHK 香港電台`
- Route Path: `/rthk/news/:lang/:category`
- Route Name: `News`
- Example: `/rthk/news/hk/international`
- URL: `rthk.hk`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `KeiLongW`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
RTHK offical provides full text RSS, check the offical website for detail information: <https://news.rthk.hk/rthk/en/rss.htm>

This route adds the missing photo and Link element. (Offical RSS doesn't have Link element may cause issue on some RSS client)

| local      | greaterchina       | international | finance      | sport      |
| ---------- | ------------------ | ------------- | ------------ | ---------- |
| Local News | Greater China News | World News    | Finance News | Sport News |

## Parameters
- `lang`: Language，Traditional Chinese`hk`，English`en`
- `category`: Category


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "RTHK offical provides full text RSS, check the offical website for detail information: <https://news.rthk.hk/rthk/en/rss.htm>\n\nThis route adds the missing photo and Link element. (Offical RSS doesn't have Link element may cause issue on some RSS client)\n\n| local      | greaterchina       | international | finance      | sport      |\n| ---------- | ------------------ | ------------- | ------------ | ---------- |\n| Local News | Greater China News | World News    | Finance News | Sport News |",
  "example": "/rthk/news/hk/international",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "KeiLongW"
  ],
  "name": "News",
  "parameters": {
    "category": "Category",
    "lang": "Language，Traditional Chinese`hk`，English`en`"
  },
  "path": "/news/:lang/:category",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
