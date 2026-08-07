# YouTube - Playlist

## Coverage
`index-only`

## Route
- Namespace: `youtube`
- Namespace Name: `YouTube`
- Route Path: `/youtube/playlist/:id/:embed?`
- Route Name: `Playlist`
- Example: `/youtube/playlist/PLqQ1RwlxOgeLTJ1f3fNMSwhjVgaWKo_9Z`
- URL: `youtube.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `HenryQW`
- Source Location: `playlist.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: YouTube playlist id
- `embed`: Default to embed the video, set to any value to disable embedding


## Features
- `requireConfig`: [{"description": " YouTube API Key, support multiple keys, split them with `,`, [API Key application](https://console.developers.google.com/)", "name": "YOUTUBE_KEY", "optional": true}]
- `requirePuppeteer`: false
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
    "social-media",
    "popular"
  ],
  "example": "/youtube/playlist/PLqQ1RwlxOgeLTJ1f3fNMSwhjVgaWKo_9Z",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": " YouTube API Key, support multiple keys, split them with `,`, [API Key application](https://console.developers.google.com/)",
        "name": "YOUTUBE_KEY",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1556,
  "location": "playlist.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "Playlist",
  "parameters": {
    "embed": "Default to embed the video, set to any value to disable embedding",
    "id": "YouTube playlist id"
  },
  "path": "/playlist/:id/:embed?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "王局拍案 by 王志安 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63845323989307392",
      "image": "https://i.ytimg.com/pl_c/PL3bAfMXyZjrPfLIHtd6Phb4R1gBswybSq/studio_square_thumbnail.jpg?sqp=CJGcrNEG-oaymwEICNAFENAFSFqi85f_AwYImOKvqwY=&rs=AOn4CLCz73hsy_mKdW3pSKGouyHimTKHVg",
      "ownerUserId": null,
      "siteUrl": "https://www.youtube.com/playlist?list=PL3bAfMXyZjrPfLIHtd6Phb4R1gBswybSq",
      "title": "王局拍案 by 王志安 - YouTube",
      "type": "feed",
      "url": "rsshub://youtube/playlist/PL3bAfMXyZjrPfLIHtd6Phb4R1gBswybSq"
    },
    {
      "description": "付鹏说 by Since1982 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "93660941816522752",
      "image": "https://i.ytimg.com/vi/m7tfUrsJsrw/hqdefault.jpg?sqp=-oaymwExCNACELwBSFryq4qpAyMIARUAAIhCGAHwAQH4Af4JgALQBYoCDAgAEAEYYyBjKGMwDw==&rs=AOn4CLAzP1etQerVVHfma9Gn-2IH3klTkA",
      "ownerUserId": null,
      "siteUrl": "https://www.youtube.com/playlist?list=PLjzImVTiIJZn_esvTZ7KH5RCngxPOc7-i",
      "title": "付鹏说 by Since1982 - YouTube",
      "type": "feed",
      "url": "rsshub://youtube/playlist/PLjzImVTiIJZn_esvTZ7KH5RCngxPOc7-i"
    }
  ],
  "view": 3
}
```
