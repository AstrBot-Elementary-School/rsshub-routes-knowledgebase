# Yahoo - Finance news (Hong Kong)

## Coverage
`index-only`

## Route
- Namespace: `yahoo`
- Namespace Name: `Yahoo`
- Route Path: `/yahoo/finance/hk/:topic?`
- Route Name: `Finance news (Hong Kong)`
- Example: `/yahoo/finance/hk/latest-news`
- URL: `news.yahoo.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `pseudoyu`
- Source Location: `finance-hk.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: Topic slug from the Yahoo Finance Hong Kong URL, defaults to latest-news.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `hk.finance.yahoo.com/topic/:topic`
- `target`: `/finance/hk/:topic`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/yahoo/finance/hk/latest-news",
  "heat": 1,
  "location": "finance-hk.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "Finance news (Hong Kong)",
  "parameters": {
    "topic": "Topic slug from the Yahoo Finance Hong Kong URL, defaults to latest-news."
  },
  "path": "/finance/hk/:topic?",
  "radar": [
    {
      "source": [
        "hk.finance.yahoo.com/topic/:topic"
      ],
      "target": "/finance/hk/:topic"
    }
  ],
  "topFeeds": []
}
```
