# Twitch - Channel Video

## Coverage
`index-only`

## Route
- Namespace: `twitch`
- Namespace Name: `Twitch`
- Route Path: `/twitch/video/:login/:filter?`
- Route Name: `Channel Video`
- Example: `/twitch/video/riotgames/highlights`
- URL: `www.twitch.tv`
- Language: `_None_`
- Categories: `live`
- Maintainers: `hoilc`
- Source Location: `video.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `login`: Twitch username
- `filter`: {"default": "all", "description": "Video type, Default to all", "options": [{"label": "Archive", "value": "archive"}, {"label": "Highlights", "value": "highlights"}, {"label": "All", "value": "all"}]}


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
  - `www.twitch.tv/:login/videos`
- `target`: `/video/:login`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "example": "/twitch/video/riotgames/highlights",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 57,
  "location": "video.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "Channel Video",
  "parameters": {
    "filter": {
      "default": "all",
      "description": "Video type, Default to all",
      "options": [
        {
          "label": "Archive",
          "value": "archive"
        },
        {
          "label": "Highlights",
          "value": "highlights"
        },
        {
          "label": "All",
          "value": "all"
        }
      ]
    },
    "login": "Twitch username"
  },
  "path": "/video/:login/:filter?",
  "radar": [
    {
      "source": [
        "www.twitch.tv/:login/videos"
      ],
      "target": "/video/:login"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Twitch - Riot Games - Recent highlights and uploads - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59281409354376192",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.twitch.tv/riotgames",
      "title": "Twitch - Riot Games - Recent highlights and uploads",
      "type": "feed",
      "url": "rsshub://twitch/video/riotgames/highlights"
    },
    {
      "description": "Twitch - 陈一发儿放映室 - All videos - Powered by RSSHub",
      "errorAt": "2026-07-08T00:19:30.855Z",
      "errorMessage": "Cannot read properties of undefined (reading 'user')\n",
      "id": "68185461739717632",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.twitch.tv/thebs_chen",
      "title": "Twitch - 陈一发儿放映室 - All videos",
      "type": "feed",
      "url": "rsshub://twitch/video/thebs_chen/all"
    }
  ],
  "view": 3
}
```
