# YouTube - Channel with user handle

## Coverage
`index-only`

## Route
- Namespace: `youtube`
- Namespace Name: `YouTube`
- Route Path: `/youtube/user/:username/:routeParams?`
- Route Name: `Channel with user handle`
- Example: `/youtube/user/@JFlaMusic`
- URL: `youtube.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `DIYgod, pseudoyu`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
::: tip Parameter

| Name         | Description                                                                        | Default |
| ------------ | ---------------------------------------------------------------------------------- | ------- |
| embed        | Whether to embed the video, fill in any value to disable embedding                 | embed   |
| filterShorts | Whether to filter out shorts from the feed, fill in any falsy value to show shorts | true    |

:::

## Parameters
- `username`: YouTuber handle with @
- `routeParams`: Extra parameters, see the table below


## Features
- `requireConfig`: [{"description": " YouTube API Key, support multiple keys, split them with `,`, [API Key application](https://console.developers.google.com/)", "name": "YOUTUBE_KEY", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.youtube.com/user/:username`
  - `www.youtube.com/:username`
  - `www.youtube.com/:username/videos`
- `target`: `/user/:username`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "description": "::: tip Parameter\n\n| Name         | Description                                                                        | Default |\n| ------------ | ---------------------------------------------------------------------------------- | ------- |\n| embed        | Whether to embed the video, fill in any value to disable embedding                 | embed   |\n| filterShorts | Whether to filter out shorts from the feed, fill in any falsy value to show shorts | true    |\n\n:::",
  "example": "/youtube/user/@JFlaMusic",
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
  "heat": 389001,
  "location": "user.ts",
  "maintainers": [
    "DIYgod",
    "pseudoyu"
  ],
  "name": "Channel with user handle",
  "parameters": {
    "routeParams": "Extra parameters, see the table below",
    "username": "YouTuber handle with @"
  },
  "path": "/user/:username/:routeParams?",
  "radar": [
    {
      "source": [
        "www.youtube.com/user/:username",
        "www.youtube.com/:username",
        "www.youtube.com/:username/videos"
      ],
      "target": "/user/:username"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Andrej Karpathy - YouTube - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60991924147702784",
      "image": "https://yt3.googleusercontent.com/ytc/AIdro_nDvyq2NoPL626bk1IbxQ94SfQsD-B0qgZchghtQNkLWoEz=s900-c-k-c0x00ffffff-no-rj",
      "ownerUserId": null,
      "siteUrl": "https://www.youtube.com/@AndrejKarpathy",
      "title": "Andrej Karpathy - YouTube",
      "type": "feed",
      "url": "rsshub://youtube/user/@AndrejKarpathy"
    },
    {
      "description": "We’re an AI safety and research company. Talk to our AI assistant Claude on claude.com. Download Claude on desktop, iOS, or Android. We believe AI will have a vast impact on the world. Anthropic is dedicated to building systems that people can rely on and generating research about the opportunities and risks of AI. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57461667496141824",
      "image": "https://yt3.googleusercontent.com/ux-GXUpB4PkI-qXVOpj9gGEiCkytT0Q78ka4srlxOm_Y3m1gEh5qy8Vu6vTjGSDztMT0NybtC7I=s900-c-k-c0x00ffffff-no-rj",
      "ownerUserId": null,
      "siteUrl": "https://www.youtube.com/@anthropic-ai",
      "title": "Anthropic - YouTube",
      "type": "feed",
      "url": "rsshub://youtube/user/%40anthropic-ai"
    }
  ],
  "view": 3
}
```
