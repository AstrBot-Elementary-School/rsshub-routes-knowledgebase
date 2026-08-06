# COLAMANGA - Manga

## Coverage
`index-only`

## Route
- Namespace: `colamanga`
- Namespace Name: `COLAMANGA`
- Route Path: `/colamanga/:id`
- Route Name: `Manga`
- Example: `/colamanga/manga-qq978758`
- URL: `www.colamanga.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `machsix`
- Source Location: `manga.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 漫画id


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.colamanga.com/:id/`
- `target`: `/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/colamanga/manga-qq978758",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 147,
  "location": "manga.ts",
  "maintainers": [
    "machsix"
  ],
  "name": "Manga",
  "parameters": {
    "id": "漫画id"
  },
  "path": "/:id",
  "radar": [
    {
      "source": [
        "www.colamanga.com/:id/"
      ],
      "target": "/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "蓝溪镇 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66031206886221870",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.colamanga.com/manga-lw40653",
      "title": "蓝溪镇",
      "type": "feed",
      "url": "rsshub://colamanga/manga-lw40653"
    },
    {
      "description": "一人之下 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "52427118129605632",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.colamanga.com/manga-fb45571",
      "title": "一人之下",
      "type": "feed",
      "url": "rsshub://colamanga/manga-fb45571"
    }
  ]
}
```
