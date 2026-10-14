# Daily.dev - Squads

## Coverage
`index-only`

## Route
- Namespace: `daily`
- Namespace Name: `Daily.dev`
- Route Path: `/daily/squads/:squads`
- Route Name: `Squads`
- Example: `/daily/squads/watercooler`
- URL: `app.daily.dev/squads/discover`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Rjnishant530`
- Source Location: `squads.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `daily.dev/squads/:squads`
- `target`: `/squads/:squads`
### Rule 2
- `source`:
  - `app.daily.dev/squads/:squads`
- `target`: `/squads/:squads`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/daily/squads/watercooler",
  "heat": 0,
  "location": "squads.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "Squads",
  "path": "/squads/:squads",
  "radar": [
    {
      "source": [
        "daily.dev/squads/:squads"
      ],
      "target": "/squads/:squads"
    },
    {
      "source": [
        "app.daily.dev/squads/:squads"
      ],
      "target": "/squads/:squads"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "app.daily.dev/squads/discover",
  "view": 0
}
```
