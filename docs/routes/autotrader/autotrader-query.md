# AutoTrader - Search

## Coverage
`index-only`

## Route
- Namespace: `autotrader`
- Namespace Name: `AutoTrader`
- Route Path: `/autotrader/:query`
- Route Name: `Search`
- Example: `/autotrader/radius=50&postcode=sw1a1aa&price-to=9000&year-from=2012&body-type=Hatchback&transmission=Automatic&exclude-writeoff-categories=on`
- URL: `www.autotrader.co.uk`
- Language: `_None_`
- Categories: `other`
- Maintainers: `HenryQW`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
1. Conduct a search with desired filters on AutoTrader
2. Copy everything in the URL after `?`, for example: `https://www.autotrader.co.uk/car-search?radius=50&postcode=sw1a1aa&price-to=9000&year-from=2012&body-type=Hatchback&transmission=Automatic&exclude-writeoff-categories=on` will produce `radius=50&postcode=sw1a1aa&price-to=9000&year-from=2012&body-type=Hatchback&transmission=Automatic&exclude-writeoff-categories=on`

## Parameters
- `query`: the search query


## Features
- `requirePuppeteer`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "1. Conduct a search with desired filters on AutoTrader\n2. Copy everything in the URL after `?`, for example: `https://www.autotrader.co.uk/car-search?radius=50&postcode=sw1a1aa&price-to=9000&year-from=2012&body-type=Hatchback&transmission=Automatic&exclude-writeoff-categories=on` will produce `radius=50&postcode=sw1a1aa&price-to=9000&year-from=2012&body-type=Hatchback&transmission=Automatic&exclude-writeoff-categories=on`",
  "example": "/autotrader/radius=50&postcode=sw1a1aa&price-to=9000&year-from=2012&body-type=Hatchback&transmission=Automatic&exclude-writeoff-categories=on",
  "features": {
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "Search",
  "parameters": {
    "query": "the search query"
  },
  "path": "/:query",
  "topFeeds": []
}
```
