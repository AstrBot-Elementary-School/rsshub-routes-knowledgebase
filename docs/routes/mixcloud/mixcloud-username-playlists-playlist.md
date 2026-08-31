# Mixcloud - Playlist

## Coverage
`index-only`

## Route
- Namespace: `mixcloud`
- Namespace Name: `Mixcloud`
- Route Path: `/mixcloud/:username/playlists/:playlist`
- Route Name: `Playlist`
- Example: `/mixcloud/dholbach/playlists/ecclectic-dance`
- URL: `www.mixcloud.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `Misaka13514`
- Source Location: `user-playlist.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: Username, can be found in URL
- `playlist`: Playlist slug, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `mixcloud.com/:username/playlists/:playlist`
### Rule 2
- `source`:
  - `www.mixcloud.com/:username/playlists/:playlist`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/mixcloud/dholbach/playlists/ecclectic-dance",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "user-playlist.ts",
  "maintainers": [
    "Misaka13514"
  ],
  "name": "Playlist",
  "parameters": {
    "playlist": "Playlist slug, can be found in URL",
    "username": "Username, can be found in URL"
  },
  "path": "/:username/playlists/:playlist",
  "radar": [
    {
      "source": [
        "mixcloud.com/:username/playlists/:playlist"
      ]
    },
    {
      "source": [
        "www.mixcloud.com/:username/playlists/:playlist"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 417943956901 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
