# itch.io - Posts

## Coverage
`index-only`

## Route
- Namespace: `itch`
- Namespace Name: `itch.io`
- Route Path: `/itch/posts/:topic/:id`
- Route Name: `Posts`
- Example: `/itch/posts/9539/introduce-yourself`
- URL: `itch.io`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `posts.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: Topic id, can be found in URL
- `id`: Topic name, can be found in URL


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
  - `itch.io/t/:topic/:id`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/itch/posts/9539/introduce-yourself",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "posts.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Posts",
  "parameters": {
    "id": "Topic name, can be found in URL",
    "topic": "Topic id, can be found in URL"
  },
  "path": "/posts/:topic/:id",
  "radar": [
    {
      "source": [
        "itch.io/t/:topic/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
