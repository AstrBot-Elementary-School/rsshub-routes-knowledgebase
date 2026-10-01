# Steam - Store Search

## Coverage
`index-only`

## Route
- Namespace: `steam`
- Namespace Name: `Steam`
- Route Path: `/steam/search/:params`
- Route Name: `Store Search`
- Example: `/steam/search/sort_by=Released_DESC&tags=492&category1=10&os=linux`
- URL: `store.steampowered.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `moppman`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `params`: Query parameters for a Steam Store search.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `store.steampowered.com`
  - `store.steampowered.com/search/:params`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/steam/search/sort_by=Released_DESC&tags=492&category1=10&os=linux",
  "heat": 5,
  "location": "search.ts",
  "maintainers": [
    "moppman"
  ],
  "name": "Store Search",
  "parameters": {
    "params": "Query parameters for a Steam Store search."
  },
  "path": "/search/:params",
  "radar": [
    {
      "source": [
        "store.steampowered.com",
        "store.steampowered.com/search/:params"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Query: sort_by=Released_DESC&tags=492&category1=10&os=linux - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58377300258747392",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://store.steampowered.com/search/?sort_by=Released_DESC&tags=492&category1=10&os=linux&ignore_preferences=1",
      "title": "Steam search result",
      "type": "feed",
      "url": "rsshub://steam/search/sort_by=Released_DESC&tags=492&category1=10&os=linux"
    },
    {
      "description": "Query: sort_by=Released_DESC&tags=1716&category1=998&category3=9&supportedlang=english&ndl=1 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "156158747312015360",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://store.steampowered.com/search/?sort_by=Released_DESC&tags=1716&category1=998&category3=9&supportedlang=english&ndl=1&ignore_preferences=1",
      "title": "Steam search result",
      "type": "feed",
      "url": "rsshub://steam/search/sort_by%3DReleased_DESC%26tags%3D1716%26category1%3D998%26category3%3D9%26supportedlang%3Denglish%26ndl%3D1"
    }
  ]
}
```
