# YouTube - Live

## Coverage
`index-only`

## Route
- Namespace: `youtube`
- Namespace Name: `YouTube`
- Route Path: `/youtube/live/:username/:embed?`
- Route Name: `Live`
- Example: `/youtube/live/@GawrGura`
- URL: `youtube.com`
- Language: `_None_`
- Categories: `live`
- Maintainers: `sussurr127`
- Source Location: `live.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: YouTuber id
- `embed`: Default to embed the video, set to any value to disable embedding


## Features
- `requireConfig`: [{"description": "YouTube API Key (enable YouTube Data API v3), support multiple keys, split them with `,`, [API Key application](https://console.developers.google.com/), [YouTube Data API v3](https://console.cloud.google.com/apis/library/youtube.googleapis.com)", "name": "YOUTUBE_KEY"}]
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
    "live"
  ],
  "example": "/youtube/live/@GawrGura",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "YouTube API Key (enable YouTube Data API v3), support multiple keys, split them with `,`, [API Key application](https://console.developers.google.com/), [YouTube Data API v3](https://console.cloud.google.com/apis/library/youtube.googleapis.com)",
        "name": "YOUTUBE_KEY"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 230,
  "location": "live.ts",
  "maintainers": [
    "sussurr127"
  ],
  "name": "Live",
  "parameters": {
    "embed": "Default to embed the video, set to any value to disable embedding",
    "username": "YouTuber id"
  },
  "path": "/live/:username/:embed?",
  "topFeeds": [
    {
      "description": "$老高與小茉 Mr & Mrs Gao's live streaming status - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69051964046186496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.youtube.com/channel/UCMUnInmOkrWN4gof9KlhNmQ",
      "title": "老高與小茉 Mr & Mrs Gao's Live Status",
      "type": "feed",
      "url": "rsshub://youtube/live/@laogao"
    },
    {
      "description": "$Gawr Gura Ch. hololive-EN's live streaming status - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42001666786766848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.youtube.com/channel/UCoSrY_IQQVpmIRZ9Xf-y93g",
      "title": "Gawr Gura Ch. hololive-EN's Live Status",
      "type": "feed",
      "url": "rsshub://youtube/live/@GawrGura"
    }
  ]
}
```
