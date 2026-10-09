# Unit Image - Films

## Coverage
`index-only`

## Route
- Namespace: `unit-image`
- Namespace Name: `Unit Image`
- Route Path: `/unit-image/films/:type?`
- Route Name: `Films`
- Example: `/unit-image/films/vfx`
- URL: `www.unit-image.fr/films`
- Language: `_None_`
- Categories: `design`
- Maintainers: `MisteryMonster`
- Source Location: `films.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"description": "Films type", "options": [{"label": "vfx", "value": "vfx"}, {"label": "game-trailer", "value": "game-trailer"}, {"label": "commercials", "value": "commercials"}, {"label": "making-of", "value": "making-of"}, {"label": "events", "value": "events"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.unit-image.fr/films`
- `target`: `/films`

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "example": "/unit-image/films/vfx",
  "heat": 2,
  "location": "films.ts",
  "maintainers": [
    "MisteryMonster"
  ],
  "name": "Films",
  "parameters": {
    "type": {
      "description": "Films type",
      "options": [
        {
          "label": "vfx",
          "value": "vfx"
        },
        {
          "label": "game-trailer",
          "value": "game-trailer"
        },
        {
          "label": "commercials",
          "value": "commercials"
        },
        {
          "label": "making-of",
          "value": "making-of"
        },
        {
          "label": "events",
          "value": "events"
        }
      ]
    }
  },
  "path": "/films/:type?",
  "radar": [
    {
      "source": [
        "www.unit-image.fr/films"
      ],
      "target": "/films"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Unit Images Films - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "264257129903988740",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.unit-image.fr/films/",
      "title": "Unit Image Films",
      "type": "feed",
      "url": "rsshub://unit-image/films"
    }
  ],
  "url": "www.unit-image.fr/films"
}
```
