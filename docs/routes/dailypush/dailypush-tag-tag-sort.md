# DailyPush - Tag

## Coverage
`index-only`

## Route
- Namespace: `dailypush`
- Namespace Name: `DailyPush`
- Route Path: `/dailypush/tag/:tag/:sort?`
- Route Name: `Tag`
- Example: `/dailypush/tag/backend/trending`
- URL: `dailypush.dev`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `TheGeeKing`
- Source Location: `tags.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tag`: {"description": "Tag name"}
- `sort`: {"default": "trending", "description": "Sort order: `trending` (default) or `latest`", "options": [{"label": "Trending", "value": "trending"}, {"label": "Latest", "value": "latest"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `dailypush.dev/:tag/trending`
  - `dailypush.dev/:tag/latest`
  - `dailypush.dev/:tag`
- `target`: `/tag/:tag/:sort?`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/dailypush/tag/backend/trending",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "tags.ts",
  "maintainers": [
    "TheGeeKing"
  ],
  "name": "Tag",
  "parameters": {
    "sort": {
      "default": "trending",
      "description": "Sort order: `trending` (default) or `latest`",
      "options": [
        {
          "label": "Trending",
          "value": "trending"
        },
        {
          "label": "Latest",
          "value": "latest"
        }
      ]
    },
    "tag": {
      "description": "Tag name"
    }
  },
  "path": "/tag/:tag/:sort?",
  "radar": [
    {
      "source": [
        "dailypush.dev/:tag/trending",
        "dailypush.dev/:tag/latest",
        "dailypush.dev/:tag"
      ],
      "target": "/tag/:tag/:sort?"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
