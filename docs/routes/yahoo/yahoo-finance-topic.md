# Yahoo - Finance news

## Coverage
`index-only`

## Route
- Namespace: `yahoo`
- Namespace Name: `Yahoo`
- Route Path: `/yahoo/finance/:topic?`
- Route Name: `Finance news`
- Example: `/yahoo/finance/latest-news`
- URL: `news.yahoo.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `DIYgod`
- Source Location: `finance.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: Topic slug from the Yahoo Finance URL, defaults to latest-news.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `finance.yahoo.com/topic/:topic`
- `target`: `/finance/:topic`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/yahoo/finance/latest-news",
  "heat": 0,
  "location": "finance.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Finance news",
  "parameters": {
    "topic": "Topic slug from the Yahoo Finance URL, defaults to latest-news."
  },
  "path": "/finance/:topic?",
  "radar": [
    {
      "source": [
        "finance.yahoo.com/topic/:topic"
      ],
      "target": "/finance/:topic"
    }
  ],
  "topFeeds": []
}
```
