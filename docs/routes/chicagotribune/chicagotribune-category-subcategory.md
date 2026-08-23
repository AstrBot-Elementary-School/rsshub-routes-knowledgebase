# Chicago Tribune - News

## Coverage
`index-only`

## Route
- Namespace: `chicagotribune`
- Namespace Name: `Chicago Tribune`
- Route Path: `/chicagotribune/:category/:subcategory?`
- Route Name: `News`
- Example: `/chicagotribune/news/nation`
- URL: `www.chicagotribune.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `oppilate`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Generates full-text that the official feed doesn't provide. For instance, `https://www.chicagotribune.com/news/national/` corresponds to `/chicagotribune/news/national`.

## Parameters
- `category`: Category
- `subcategory`: Subcategory


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.chicagotribune.com/:category/:subcategory?`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Generates full-text that the official feed doesn't provide. For instance, `https://www.chicagotribune.com/news/national/` corresponds to `/chicagotribune/news/national`.",
  "example": "/chicagotribune/news/nation",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "oppilate"
  ],
  "name": "News",
  "parameters": {
    "category": "Category",
    "subcategory": "Subcategory"
  },
  "path": "/:category/:subcategory?",
  "radar": [
    {
      "source": [
        "www.chicagotribune.com/:category/:subcategory?"
      ]
    }
  ],
  "topFeeds": [],
  "url": "www.chicagotribune.com"
}
```
