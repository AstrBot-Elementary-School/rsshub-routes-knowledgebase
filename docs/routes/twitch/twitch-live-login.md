# Twitch - Live

## Coverage
`index-only`

## Route
- Namespace: `twitch`
- Namespace Name: `Twitch`
- Route Path: `/twitch/live/:login`
- Route Name: `Live`
- Example: `/twitch/live/riotgames`
- URL: `www.twitch.tv`
- Language: `_None_`
- Categories: `live`
- Maintainers: `hoilc`
- Source Location: `live.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `login`: Twitch username


## Features
- `requireConfig`: false
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
  "example": "/twitch/live/riotgames",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 305,
  "location": "live.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "Live",
  "parameters": {
    "login": "Twitch username"
  },
  "path": "/live/:login",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "neuro-sama the ai vtuber - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60683277623649280",
      "image": "https://static-cdn.jtvnw.net/jtv_user_pictures/dd956f46-3776-4dfd-8bc3-e4f74c5ede67-profile_image-300x300.png",
      "ownerUserId": null,
      "siteUrl": "https://www.twitch.tv/vedal987",
      "title": "Twitch - vedal987 - Live",
      "type": "feed",
      "url": "rsshub://twitch/live/vedal987"
    },
    {
      "description": "Welcome to the Riot Games channel, home of LoL Esports and other livestreams related to our games. For LoL Esports broadcasts, schedules, standings and advanced viewing features, head to http://lolesports.com. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "43556488621069312",
      "image": "https://static-cdn.jtvnw.net/jtv_user_pictures/35b02a12-d516-499e-90f8-7899f136fa18-profile_image-300x300.png",
      "ownerUserId": null,
      "siteUrl": "https://www.twitch.tv/riotgames",
      "title": "Twitch - Riot Games - Live",
      "type": "feed",
      "url": "rsshub://twitch/live/riotgames"
    }
  ],
  "view": 5
}
```
