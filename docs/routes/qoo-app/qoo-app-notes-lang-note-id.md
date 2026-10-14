# QooApp - Note Comments

## Coverage
`index-only`

## Route
- Namespace: `qoo-app`
- Namespace Name: `QooApp`
- Route Path: `/qoo-app/notes/:lang/note/:id`
- Route Name: `Note Comments`
- Example: `/qoo-app/notes/en/note/2329113`
- URL: `apps.qoo-app.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `TonyRL`
- Source Location: `notes/note.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `lang`: Language, see the table above, empty means `中文`
- `id`: Note ID, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/qoo-app/notes/en/note/2329113",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "notes/note.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Note Comments",
  "parameters": {
    "id": "Note ID, can be found in URL",
    "lang": "Language, see the table above, empty means `中文`"
  },
  "path": [
    "/notes/:lang/note/:id",
    "/notes/note/:id"
  ],
  "topFeeds": []
}
```
