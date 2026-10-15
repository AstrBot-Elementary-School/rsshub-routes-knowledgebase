# Premium Bandai - New Items

## Coverage
`index-only`

## Route
- Namespace: `p-bandai`
- Namespace Name: `Premium Bandai`
- Route Path: `/p-bandai/new`
- Route Name: `New Items`
- Example: `/p-bandai/new`
- URL: `p-bandai.jp/new_itemlist/`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `pseudoyu`
- Source Location: `new.tsx`
- Source Module: `_None_`

## Description
Items added in the last 10 days, with the image, the price and the start of sales or reservations.

::: warning
Premium Bandai redirects visitors outside Japan to its international site, so the instance needs a Japanese IP. You can send only these requests through a Japanese proxy with `PROXY_URI` and `PROXY_URL_REGEX=p-bandai\.jp`.

The list shortens long item names, and the item pages are behind a browser check, so full names and delivery dates are not included.
:::

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
  - `p-bandai.jp/new_itemlist`
- `target`: `/new`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "Items added in the last 10 days, with the image, the price and the start of sales or reservations.\n\n::: warning\nPremium Bandai redirects visitors outside Japan to its international site, so the instance needs a Japanese IP. You can send only these requests through a Japanese proxy with `PROXY_URI` and `PROXY_URL_REGEX=p-bandai\\.jp`.\n\nThe list shortens long item names, and the item pages are behind a browser check, so full names and delivery dates are not included.\n:::",
  "example": "/p-bandai/new",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "new.tsx",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "New Items",
  "parameters": {},
  "path": "/new",
  "radar": [
    {
      "source": [
        "p-bandai.jp/new_itemlist"
      ],
      "target": "/new"
    }
  ],
  "topFeeds": [],
  "url": "p-bandai.jp/new_itemlist/"
}
```
