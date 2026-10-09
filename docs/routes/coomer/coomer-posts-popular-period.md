# Coomer - Popular posts

## Coverage
`index-only`

## Route
- Namespace: `coomer`
- Namespace Name: `Coomer`
- Route Path: `/coomer/posts/popular/:period?`
- Route Name: `Popular posts`
- Example: `/coomer/posts/popular/1d`
- URL: `coomer.st`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `DIYgod`
- Source Location: `popular.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `period`: {"default": "1d", "description": "Popular ranking period.", "options": [{"label": "1d", "value": "1d"}, {"label": "1w", "value": "1w"}, {"label": "1m", "value": "1m"}]}


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `coomer.st/posts/popular`
- `target`: `/posts/popular`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/coomer/posts/popular/1d",
  "features": {
    "nsfw": true
  },
  "heat": 0,
  "location": "popular.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Popular posts",
  "parameters": {
    "period": {
      "default": "1d",
      "description": "Popular ranking period.",
      "options": [
        {
          "label": "1d",
          "value": "1d"
        },
        {
          "label": "1w",
          "value": "1w"
        },
        {
          "label": "1m",
          "value": "1m"
        }
      ]
    }
  },
  "path": "/posts/popular/:period?",
  "radar": [
    {
      "source": [
        "coomer.st/posts/popular"
      ],
      "target": "/posts/popular"
    }
  ],
  "topFeeds": []
}
```
