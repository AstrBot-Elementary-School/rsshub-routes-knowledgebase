# Spotify - Personal Top Tracks

## Coverage
`index-only`

## Route
- Namespace: `spotify`
- Namespace Name: `Spotify`
- Route Path: `/spotify/top/tracks`
- Route Name: `Personal Top Tracks`
- Example: `/spotify/top/tracks`
- URL: `open.spotify.com/`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `outloudvi`
- Source Location: `tracks-top.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "", "name": "SPOTIFY_CLIENT_ID"}, {"description": "", "name": "SPOTIFY_CLIENT_SECRET"}, {"description": "", "name": "SPOTIFY_REFRESHTOKEN"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `open.spotify.com/`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/spotify/top/tracks",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "SPOTIFY_CLIENT_ID"
      },
      {
        "description": "",
        "name": "SPOTIFY_CLIENT_SECRET"
      },
      {
        "description": "",
        "name": "SPOTIFY_REFRESHTOKEN"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 11,
  "location": "tracks-top.ts",
  "maintainers": [
    "outloudvi"
  ],
  "name": "Personal Top Tracks",
  "parameters": {},
  "path": "/top/tracks",
  "radar": [
    {
      "source": [
        "open.spotify.com/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "Spotify: My Top Tracks - Powered by RSSHub",
      "errorAt": "2026-03-12T15:51:13.296Z",
      "errorMessage": "[POST] \"https://accounts.spotify.com/api/token\": 400 Bad Request\n",
      "id": "57248628577921024",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "Spotify: My Top Tracks",
      "type": "feed",
      "url": "rsshub://spotify/top/tracks"
    }
  ],
  "url": "open.spotify.com/"
}
```
