# COMIC FUZ - 漫画详情

## Coverage
`index-only`

## Route
- Namespace: `comic-fuz`
- Namespace Name: `COMIC FUZ`
- Route Path: `/comic-fuz/manga/:id`
- Route Name: `漫画详情`
- Example: `/comic-fuz/manga/218`
- URL: `comic-fuz.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `xiaobailoves`
- Source Location: `manga.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: ComicFuz中对应的漫画id


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
  - `comic-fuz.com/manga/:id`
- `target`: `/manga/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/comic-fuz/manga/218",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "manga.ts",
  "maintainers": [
    "xiaobailoves"
  ],
  "name": "漫画详情",
  "parameters": {
    "id": "ComicFuz中对应的漫画id"
  },
  "path": "/manga/:id",
  "radar": [
    {
      "source": [
        "comic-fuz.com/manga/:id"
      ],
      "target": "/manga/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
