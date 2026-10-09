# Carnegie Endowment for International Peace - Expert research

## Coverage
`index-only`

## Route
- Namespace: `carnegieendowment`
- Namespace Name: `Carnegie Endowment for International Peace`
- Route Path: `/carnegieendowment/expert/:expert{.+}?`
- Route Name: `Expert research`
- Example: `/carnegieendowment/expert/china/people/michael-pettis`
- URL: `carnegieendowment.org`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `DIYgod`
- Source Location: `expert.ts`
- Source Module: `_None_`

## Description
Carnegie articles include their full text; external publications include the source-provided excerpt.

## Parameters
- `expert`: Expert profile path from the website URL, defaults to china/people/michael-pettis.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `carnegieendowment.org/:center/people/:expert`
- `target`: `/expert/:center/people/:expert`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Carnegie articles include their full text; external publications include the source-provided excerpt.",
  "example": "/carnegieendowment/expert/china/people/michael-pettis",
  "heat": 0,
  "location": "expert.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Expert research",
  "parameters": {
    "expert": "Expert profile path from the website URL, defaults to china/people/michael-pettis."
  },
  "path": "/expert/:expert{.+}?",
  "radar": [
    {
      "source": [
        "carnegieendowment.org/:center/people/:expert"
      ],
      "target": "/expert/:center/people/:expert"
    }
  ],
  "topFeeds": []
}
```
