# Spotify - Artist Albums

## Coverage
`index-only`

## Route
- Namespace: `spotify`
- Namespace Name: `Spotify`
- Route Path: `/spotify/artist/:id`
- Route Name: `Artist Albums`
- Example: `/spotify/artist/6k9TBCxyr4bXwZ8Y21Kwn1`
- URL: `open.spotify.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `outloudvi`
- Source Location: `artist.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Artist ID


## Features
- `requireConfig`: [{"description": "", "name": "SPOTIFY_CLIENT_ID"}, {"description": "", "name": "SPOTIFY_CLIENT_SECRET"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `open.spotify.com/artist/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/spotify/artist/6k9TBCxyr4bXwZ8Y21Kwn1",
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
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 418,
  "location": "artist.ts",
  "maintainers": [
    "outloudvi"
  ],
  "name": "Artist Albums",
  "parameters": {
    "id": "Artist ID"
  },
  "path": "/artist/:id",
  "radar": [
    {
      "source": [
        "open.spotify.com/artist/:id"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "Albums of Taylor Swift - Powered by RSSHub",
      "errorAt": "2026-03-10T15:04:10.929Z",
      "errorMessage": "[GET] \"https://api.spotify.com/v1/artists/06HL4z0CvFAxyc27GXpf02\": 403 Forbidden\n",
      "id": "55152034158156800",
      "image": "https://i.scdn.co/image/ab6761610000e5ebe2e8e7ff002a4afda1c7147e",
      "ownerUserId": null,
      "siteUrl": "https://open.spotify.com/artist/06HL4z0CvFAxyc27GXpf02",
      "title": "Albums of Taylor Swift",
      "type": "feed",
      "url": "rsshub://spotify/artist/06HL4z0CvFAxyc27GXpf02"
    },
    {
      "description": "Albums of Jay Chou - Powered by RSSHub",
      "errorAt": "2026-03-13T13:28:45.639Z",
      "errorMessage": "Spotify public RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#route-specific-configurations\">relevant config</a>\n[GET] \"https://api.spotify.com/v1/artists/2elBjNSdBE2Y3f0j1mjrql\": 403 Forbidden\n",
      "id": "54863626825990144",
      "image": "https://i.scdn.co/image/ab6761610000e5eb02b3aa55ba238b2ceafb09da",
      "ownerUserId": null,
      "siteUrl": "https://open.spotify.com/artist/2elBjNSdBE2Y3f0j1mjrql",
      "title": "Albums of Jay Chou",
      "type": "feed",
      "url": "rsshub://spotify/artist/2elBjNSdBE2Y3f0j1mjrql"
    }
  ],
  "view": 4
}
```
