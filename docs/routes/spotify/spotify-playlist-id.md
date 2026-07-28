# Spotify - Playlist

## Coverage
`index-only`

## Route
- Namespace: `spotify`
- Namespace Name: `Spotify`
- Route Path: `/spotify/playlist/:id`
- Route Name: `Playlist`
- Example: `/spotify/playlist/4UBVy1LttvodwivPUuwJk2`
- URL: `open.spotify.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `outloudvi`
- Source Location: `playlist.ts`
- Source Module: `_None_`

## Description
::: warning
Due to [limitations by Spotify](https://developer.spotify.com/blog/2024-11-27-changes-to-the-web-api), this endpoint is unable to access "Algorithmic and Spotify-owned editorial playlists".
:::

## Parameters
- `id`: Playlist ID


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
  - `open.spotify.com/playlist/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: warning\nDue to [limitations by Spotify](https://developer.spotify.com/blog/2024-11-27-changes-to-the-web-api), this endpoint is unable to access \"Algorithmic and Spotify-owned editorial playlists\".\n:::",
  "example": "/spotify/playlist/4UBVy1LttvodwivPUuwJk2",
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
  "heat": 225,
  "location": "playlist.ts",
  "maintainers": [
    "outloudvi"
  ],
  "name": "Playlist",
  "parameters": {
    "id": "Playlist ID"
  },
  "path": "/playlist/:id",
  "radar": [
    {
      "source": [
        "open.spotify.com/playlist/:id"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "80后最愛流行歌曲 - Powered by RSSHub",
      "errorAt": "2026-03-10T02:36:28.213Z",
      "errorMessage": "Spotify public RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#route-specific-configurations\">relevant config</a>\n502 \n[GET] \"https://api.spotify.com/v1/playlists/1dHPmj7pko81BDKJKtbZI0?si=jiiWKPZvQkqPgY_2__fhzA&pi=a-V-doWJgCTrKF\": 403 Forbidden\n",
      "id": "67455875316275200",
      "image": "https://mosaic.scdn.co/640/ab67616d00001e021666422b2fc0d7d9a0358996ab67616d00001e02736efd28176769a88b7bf474ab67616d00001e02a0156e5ccc688a02353c1a38ab67616d00001e02a7bd9c9f48507bacf9561077",
      "ownerUserId": null,
      "siteUrl": "https://open.spotify.com/playlist/1dHPmj7pko81BDKJKtbZI0",
      "title": "80后最愛流行歌曲",
      "type": "feed",
      "url": "rsshub://spotify/playlist/1dHPmj7pko81BDKJKtbZI0%3Fsi%3DjiiWKPZvQkqPgY_2__fhzA%26pi%3Da-V-doWJgCTrKF"
    },
    {
      "description": "我的 #1 歌单 - Powered by RSSHub",
      "errorAt": "2026-03-13T12:56:10.015Z",
      "errorMessage": "[GET] \"https://api.spotify.com/v1/playlists/46xeCbIm6G6fwyEnQt3jDE\": 403 Forbidden\n",
      "id": "66927900129095680",
      "image": "https://mosaic.scdn.co/640/ab67616d00001e024c71a3621790807f860013f2ab67616d00001e027cee47f72f7ba60ea64d47baab67616d00001e027e706654b5f1203c25a7d129ab67616d00001e029ad5c65b2bb5fabc66f2ae94",
      "ownerUserId": null,
      "siteUrl": "https://open.spotify.com/playlist/46xeCbIm6G6fwyEnQt3jDE",
      "title": "我的 #1 歌单",
      "type": "feed",
      "url": "rsshub://spotify/playlist/46xeCbIm6G6fwyEnQt3jDE"
    }
  ],
  "view": 4
}
```
