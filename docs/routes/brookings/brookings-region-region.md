# Brookings Institution - Regional research

## Coverage
`index-only`

## Route
- Namespace: `brookings`
- Namespace Name: `Brookings Institution`
- Route Path: `/brookings/region/:region{.+}?`
- Route Name: `Regional research`
- Example: `/brookings/region/asia-the-pacific/china`
- URL: `www.brookings.edu`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `DIYgod`
- Source Location: `region.ts`
- Source Module: `_None_`

## Description
Includes the article excerpts supplied by the official regional research search index.

## Parameters
- `region`: Region path after /regions/ in the website URL, defaults to asia-the-pacific/china


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.brookings.edu/regions/:region+`
- `target`: `/region/:region`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Includes the article excerpts supplied by the official regional research search index.",
  "example": "/brookings/region/asia-the-pacific/china",
  "heat": 0,
  "location": "region.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Regional research",
  "parameters": {
    "region": "Region path after /regions/ in the website URL, defaults to asia-the-pacific/china"
  },
  "path": "/region/:region{.+}?",
  "radar": [
    {
      "source": [
        "www.brookings.edu/regions/:region+"
      ],
      "target": "/region/:region"
    }
  ],
  "topFeeds": []
}
```
