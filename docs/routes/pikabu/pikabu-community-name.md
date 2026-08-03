# Pikabu - Community

## Coverage
`index-only`

## Route
- Namespace: `pikabu`
- Namespace Name: `Pikabu`
- Route Path: `/pikabu/community/:name`
- Route Name: `Community`
- Example: `/pikabu/community/real_true_story`
- URL: `pikabu.ru`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `community.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: Community name


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `pikabu.ru/community/:name`
- `target`: `/community/:name`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/pikabu/community/real_true_story",
  "heat": 0,
  "location": "community.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Community",
  "parameters": {
    "name": "Community name"
  },
  "path": "/community/:name",
  "radar": [
    {
      "source": [
        "pikabu.ru/community/:name"
      ],
      "target": "/community/:name"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
