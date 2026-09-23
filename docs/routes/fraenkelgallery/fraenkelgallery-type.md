# Fraenkel Gallery - Exhibitions & Conversations

## Coverage
`index-only`

## Route
- Namespace: `fraenkelgallery`
- Namespace Name: `Fraenkel Gallery`
- Route Path: `/fraenkelgallery/:type?`
- Route Name: `Exhibitions & Conversations`
- Example: `/fraenkelgallery/exhibitions`
- URL: `fraenkelgallery.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `IvanWng97`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
Exhibitions come with artist, year, type and status as categories and the full exhibition page including all images.

## Parameters
- `type`: `exhibitions` (default) or `posts` (the Conversations blog)


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `fraenkelgallery.com/exhibitions`
  - `fraenkelgallery.com/`
- `target`: `/exhibitions`
### Rule 2
- `source`:
  - `fraenkelgallery.com/conversations`
- `target`: `/posts`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "Exhibitions come with artist, year, type and status as categories and the full exhibition page including all images.",
  "example": "/fraenkelgallery/exhibitions",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.tsx",
  "maintainers": [
    "IvanWng97"
  ],
  "name": "Exhibitions & Conversations",
  "parameters": {
    "type": "`exhibitions` (default) or `posts` (the Conversations blog)"
  },
  "path": "/:type?",
  "radar": [
    {
      "source": [
        "fraenkelgallery.com/exhibitions",
        "fraenkelgallery.com/"
      ],
      "target": "/exhibitions"
    },
    {
      "source": [
        "fraenkelgallery.com/conversations"
      ],
      "target": "/posts"
    }
  ],
  "topFeeds": [],
  "view": 2
}
```
