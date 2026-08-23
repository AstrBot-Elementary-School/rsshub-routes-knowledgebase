# MIT Technology Review - Topics

## Coverage
`index-only`

## Route
- Namespace: `technologyreview`
- Namespace Name: `MIT Technology Review`
- Route Path: `/technologyreview/:category_name`
- Route Name: `Topics`
- Example: `/technologyreview/artificial-intelligence`
- URL: `www.technologyreview.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `laampui`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
| Category                  | `:category_name`        |
| ------------------------- | ----------------------- |
| Artificial intelligence   | artificial-intelligence |
| Biotechnology and health  | biotechnology           |
| Business                  | business                |
| Climate change and energy | climate-change          |
| Computing                 | computing               |
| Culture                   | culture                 |
| Policy                    | policy                  |
| Space                     | space                   |

## Parameters
- `category_name`: see below


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.technologyreview.com/topic/:category_name`
- `target`: `/:category_name`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "| Category                  | `:category_name`        |\n| ------------------------- | ----------------------- |\n| Artificial intelligence   | artificial-intelligence |\n| Biotechnology and health  | biotechnology           |\n| Business                  | business                |\n| Climate change and energy | climate-change          |\n| Computing                 | computing               |\n| Culture                   | culture                 |\n| Policy                    | policy                  |\n| Space                     | space                   |",
  "example": "/technologyreview/artificial-intelligence",
  "heat": 0,
  "location": "topic.ts",
  "maintainers": [
    "laampui"
  ],
  "name": "Topics",
  "parameters": {
    "category_name": "see below"
  },
  "path": "/:category_name",
  "radar": [
    {
      "source": [
        "www.technologyreview.com/topic/:category_name"
      ],
      "target": "/:category_name"
    }
  ],
  "topFeeds": [],
  "url": "www.technologyreview.com"
}
```
