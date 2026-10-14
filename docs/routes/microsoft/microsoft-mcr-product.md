# Microsoft - Product tags in mcr.microsoft.com

## Coverage
`index-only`

## Route
- Namespace: `microsoft`
- Namespace Name: `Microsoft`
- Route Path: `/microsoft/mcr/product/*`
- Route Name: `Product tags in mcr.microsoft.com`
- Example: `/microsoft/mcr/product/dotnet/framework/runtime`
- URL: `microsoft.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `margani`
- Source Location: `mcr.ts`
- Source Module: `_None_`

## Description
Append the repository path after `/mcr/product/`, including nested repository segments.

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
  - `mcr.microsoft.com/en-us/product/*product/tags`
- `target`: `/mcr/product/:product`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "Append the repository path after `/mcr/product/`, including nested repository segments.",
  "example": "/microsoft/mcr/product/dotnet/framework/runtime",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "mcr.ts",
  "maintainers": [
    "margani"
  ],
  "name": "Product tags in mcr.microsoft.com",
  "path": "/mcr/product/*",
  "radar": [
    {
      "source": [
        "mcr.microsoft.com/en-us/product/*product/tags"
      ],
      "target": "/mcr/product/:product"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
