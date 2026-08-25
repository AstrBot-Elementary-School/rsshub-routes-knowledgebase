# Company 3 - Video Categories

## Coverage
`index-only`

## Route
- Namespace: `company3`
- Namespace Name: `Company 3`
- Route Path: `/company3/:category?`
- Route Name: `Video Categories`
- Example: `/company3/features`
- URL: `www.company3.com`
- Language: `_None_`
- Categories: `design`
- Maintainers: `MisteryMonster`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"default": "commercials", "description": "Category", "options": [{"label": "commercials", "value": "commercials"}, {"label": "features", "value": "features"}, {"label": "television", "value": "television"}, {"label": "sound", "value": "sound"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.company3.com/video-categories/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "example": "/company3/features",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "MisteryMonster"
  ],
  "name": "Video Categories",
  "parameters": {
    "category": {
      "default": "commercials",
      "description": "Category",
      "options": [
        {
          "label": "commercials",
          "value": "commercials"
        },
        {
          "label": "features",
          "value": "features"
        },
        {
          "label": "television",
          "value": "television"
        },
        {
          "label": "sound",
          "value": "sound"
        }
      ]
    }
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.company3.com/video-categories/:category"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.company3.com"
}
```
