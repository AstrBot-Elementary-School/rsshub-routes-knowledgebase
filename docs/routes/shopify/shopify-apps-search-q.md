# Shopify - App store search

## Coverage
`index-only`

## Route
- Namespace: `shopify`
- Namespace Name: `Shopify`
- Route Path: `/shopify/apps/search/:q`
- Route Name: `App store search`
- Example: `/shopify/apps/search/flow`
- URL: `shopify.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `PrintNow`
- Source Location: `apps/search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `q`: 需要搜索的 App


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `apps.shopify.com/search`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/shopify/apps/search/flow",
  "heat": 0,
  "location": "apps/search.ts",
  "maintainers": [
    "PrintNow"
  ],
  "name": "App store search",
  "parameters": {
    "q": "需要搜索的 App"
  },
  "path": "/apps/search/:q",
  "radar": [
    {
      "source": [
        "apps.shopify.com/search"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
