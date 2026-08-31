# MangaDex - MDList Feed

## Coverage
`index-only`

## Route
- Namespace: `mangadex`
- Namespace Name: `MangaDex`
- Route Path: `/mangadex/mdlist/:id/:lang?`
- Route Name: `MDList Feed`
- Example: `/mangadex/mdlist/10cca803-8dc9-4f0e-86a8-6659a3ce5188?limit=10&private=true`
- URL: `mangadex.org`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `chrisis58`
- Source Location: `mdlist/feed.ts`
- Source Module: `_None_`

## Description
Sepcific MangaDex MDList Feed

## Parameters
- `id`: {"description": "The list id of the manga list"}
- `private`: {"description": "(Query Param) Needed to access private lists, any value will be treated as true"}


## Features
- `requireConfig`: [{"description": "MangaDex Username, required when refresh-token is not set and the list is private", "name": "MANGADEX_USERNAME", "optional": true}, {"description": "MangaDex Password, required when refresh-token is not set and the list is private", "name": "MANGADEX_PASSWORD", "optional": true}, {"description": "MangaDex Client ID, required when the list is private", "name": "MANGADEX_CLIENT_ID", "optional": true}, {"description": "MangaDex Client Secret, required when the list is private", "name": "MANGADEX_CLIENT_SECRET", "optional": true}, {"description": "MangaDex Refresh Token, required when username and password are not set and the list is private", "name": "MANGADEX_REFRESH_TOKEN", "optional": true}]
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `mangadex.org/list/:id/:suffix`
- `target`: `/mdlist/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "Sepcific MangaDex MDList Feed",
  "example": "/mangadex/mdlist/10cca803-8dc9-4f0e-86a8-6659a3ce5188?limit=10&private=true",
  "features": {
    "nsfw": true,
    "requireConfig": [
      {
        "description": "MangaDex Username, required when refresh-token is not set and the list is private",
        "name": "MANGADEX_USERNAME",
        "optional": true
      },
      {
        "description": "MangaDex Password, required when refresh-token is not set and the list is private",
        "name": "MANGADEX_PASSWORD",
        "optional": true
      },
      {
        "description": "MangaDex Client ID, required when the list is private",
        "name": "MANGADEX_CLIENT_ID",
        "optional": true
      },
      {
        "description": "MangaDex Client Secret, required when the list is private",
        "name": "MANGADEX_CLIENT_SECRET",
        "optional": true
      },
      {
        "description": "MangaDex Refresh Token, required when username and password are not set and the list is private",
        "name": "MANGADEX_REFRESH_TOKEN",
        "optional": true
      }
    ]
  },
  "heat": 1,
  "location": "mdlist/feed.ts",
  "maintainers": [
    "chrisis58"
  ],
  "name": "MDList Feed",
  "parameters": {
    "id": {
      "description": "The list id of the manga list"
    },
    "private": {
      "description": "(Query Param) Needed to access private lists, any value will be treated as true"
    }
  },
  "path": "/mdlist/:id/:lang?",
  "radar": [
    {
      "source": [
        "mangadex.org/list/:id/:suffix"
      ],
      "target": "/mdlist/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "The latest updates of all the manga in a sepcific list - Powered by RSSHub",
      "errorAt": "2026-07-29T22:08:33.885Z",
      "errorMessage": "Failed to fetch\n",
      "id": "182814965369088000",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mangadex.org/list/06f15fee-e4a5-4c22-956d-315588c2afcf?tab=feed",
      "title": "MDList - Followed by Crazyharp",
      "type": "feed",
      "url": "rsshub://mangadex/mdlist/06f15fee-e4a5-4c22-956d-315588c2afcf"
    }
  ]
}
```
