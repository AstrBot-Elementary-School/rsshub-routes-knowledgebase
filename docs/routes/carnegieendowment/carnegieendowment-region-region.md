# Carnegie Endowment for International Peace - Regional research

## Coverage
`index-only`

## Route
- Namespace: `carnegieendowment`
- Namespace Name: `Carnegie Endowment for International Peace`
- Route Path: `/carnegieendowment/region/:region?`
- Route Name: `Regional research`
- Example: `/carnegieendowment/region/china`
- URL: `carnegieendowment.org`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `DIYgod`
- Source Location: `region.ts`
- Source Module: `_None_`

## Description
Includes research, commentary, and media appearances listed by the website. Carnegie articles include their full text; external publications include the source-provided excerpt.

## Parameters
- `region`: Region slug from the website URL, defaults to china.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `carnegieendowment.org/regions/:region`
- `target`: `/region/:region`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Includes research, commentary, and media appearances listed by the website. Carnegie articles include their full text; external publications include the source-provided excerpt.",
  "example": "/carnegieendowment/region/china",
  "heat": 0,
  "location": "region.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Regional research",
  "parameters": {
    "region": "Region slug from the website URL, defaults to china."
  },
  "path": "/region/:region?",
  "radar": [
    {
      "source": [
        "carnegieendowment.org/regions/:region"
      ],
      "target": "/region/:region"
    }
  ],
  "topFeeds": []
}
```
