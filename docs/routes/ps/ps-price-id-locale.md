# PlayStation Store - Game Price

## Coverage
`index-only`

## Route
- Namespace: `ps`
- Namespace Name: `PlayStation Store`
- Route Path: `/ps/price/:id/:locale?`
- Route Name: `Game Price`
- Example: `/ps/price/10001538`
- URL: `store.playstation.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `pseudoyu`
- Source Location: `price.tsx`
- Source Module: `_None_`

## Description
A concept ID lists every edition of the game, and a product ID lists only that product. A new item appears whenever the price or the end of the offer changes. PlayStation Plus prices and trials are not included.

## Parameters
- `id`: Concept or product ID from the store URL, such as `10001538` in `https://store.playstation.com/en-us/concept/10001538`
- `locale`: Store locale from the URL, `en-us` by default


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
  - `store.playstation.com/:locale/concept/:id`
  - `store.playstation.com/:locale/product/:id`
- `target`: `/price/:id/:locale`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "A concept ID lists every edition of the game, and a product ID lists only that product. A new item appears whenever the price or the end of the offer changes. PlayStation Plus prices and trials are not included.",
  "example": "/ps/price/10001538",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "price.tsx",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "Game Price",
  "parameters": {
    "id": "Concept or product ID from the store URL, such as `10001538` in `https://store.playstation.com/en-us/concept/10001538`",
    "locale": "Store locale from the URL, `en-us` by default"
  },
  "path": "/price/:id/:locale?",
  "radar": [
    {
      "source": [
        "store.playstation.com/:locale/concept/:id",
        "store.playstation.com/:locale/product/:id"
      ],
      "target": "/price/:id/:locale"
    }
  ],
  "topFeeds": [],
  "url": "store.playstation.com",
  "view": 5
}
```
