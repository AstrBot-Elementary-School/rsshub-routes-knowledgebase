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
  "heat": 1,
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
  "topFeeds": [
    {
      "description": "Rotten Tomatoes - Popular streaming movies - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1334059182004764672",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.rottentomatoes.com/browse/movies_at_home/sort:popular",
      "title": "Rotten Tomatoes - Popular streaming movies",
      "type": "feed",
      "url": "rsshub://rottentomatoes/browse/popular-streaming"
    }
  ]
}
```
