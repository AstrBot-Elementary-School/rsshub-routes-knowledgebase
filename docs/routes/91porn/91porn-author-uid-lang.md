# 91porn - Author

## Coverage
`index-only`

## Route
- Namespace: `91porn`
- Namespace Name: `91porn`
- Route Path: `/91porn/author/:uid/:lang?`
- Route Name: `Author`
- Example: `/91porn/author/2d6d2iWm4vVCwqujAZbSrKt2QJCbbaObv9HQ21Zo8wGJWudWBg`
- URL: `91porn.com/index.php`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `author.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: Author ID, can be found in URL
- `lang`: Language, see above, `en_US` by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `91porn.com/index.php`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/91porn/author/2d6d2iWm4vVCwqujAZbSrKt2QJCbbaObv9HQ21Zo8wGJWudWBg",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "author.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Author",
  "parameters": {
    "lang": "Language, see above, `en_US` by default ",
    "uid": "Author ID, can be found in URL"
  },
  "path": "/author/:uid/:lang?",
  "radar": [
    {
      "source": [
        "91porn.com/index.php"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "91porn.com/index.php"
}
```
