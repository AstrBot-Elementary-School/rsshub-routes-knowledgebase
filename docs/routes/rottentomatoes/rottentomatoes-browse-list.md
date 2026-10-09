# Rotten Tomatoes - Movie and TV lists

## Coverage
`index-only`

## Route
- Namespace: `rottentomatoes`
- Namespace Name: `Rotten Tomatoes`
- Route Path: `/rottentomatoes/browse/:list?`
- Route Name: `Movie and TV lists`
- Example: `/rottentomatoes/browse`
- URL: `rottentomatoes.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `DIYgod`
- Source Location: `browse.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `list`: {"default": "new-in-theaters", "description": "Movie or TV list.", "options": [{"label": "New movies in theaters", "value": "new-in-theaters"}, {"label": "Popular movies in theaters", "value": "popular-in-theaters"}, {"label": "Popular streaming movies", "value": "popular-streaming"}, {"label": "Certified Fresh movies", "value": "certified-fresh"}, {"label": "Popular TV shows", "value": "popular-tv"}, {"label": "New TV shows", "value": "new-tv"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `rottentomatoes.com/browse`
- `target`: `/browse`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/rottentomatoes/browse",
  "heat": 0,
  "location": "browse.tsx",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Movie and TV lists",
  "parameters": {
    "list": {
      "default": "new-in-theaters",
      "description": "Movie or TV list.",
      "options": [
        {
          "label": "New movies in theaters",
          "value": "new-in-theaters"
        },
        {
          "label": "Popular movies in theaters",
          "value": "popular-in-theaters"
        },
        {
          "label": "Popular streaming movies",
          "value": "popular-streaming"
        },
        {
          "label": "Certified Fresh movies",
          "value": "certified-fresh"
        },
        {
          "label": "Popular TV shows",
          "value": "popular-tv"
        },
        {
          "label": "New TV shows",
          "value": "new-tv"
        }
      ]
    }
  },
  "path": "/browse/:list?",
  "radar": [
    {
      "source": [
        "rottentomatoes.com/browse"
      ],
      "target": "/browse"
    }
  ],
  "topFeeds": []
}
```
