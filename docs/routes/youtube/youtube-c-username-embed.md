# YouTube - Custom URL

## Coverage
`index-only`

## Route
- Namespace: `youtube`
- Namespace Name: `YouTube`
- Route Path: `/youtube/c/:username/:embed?`
- Route Name: `Custom URL`
- Example: `/youtube/c/YouTubeCreators`
- URL: `youtube.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `custom.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: YouTube custom URL
- `embed`: Default to embed the video, set to any value to disable embedding


## Features
- `requireConfig`: [{"description": " YouTube API Key, support multiple keys, split them with `,`, [API Key application](https://console.developers.google.com/)", "name": "YOUTUBE_KEY"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.youtube.com/c/:id`
- `target`: `/c/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/youtube/c/YouTubeCreators",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": " YouTube API Key, support multiple keys, split them with `,`, [API Key application](https://console.developers.google.com/)",
        "name": "YOUTUBE_KEY"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 92,
  "location": "custom.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Custom URL",
  "parameters": {
    "embed": "Default to embed the video, set to any value to disable embedding",
    "username": "YouTube custom URL"
  },
  "path": "/c/:username/:embed?",
  "radar": [
    {
      "source": [
        "www.youtube.com/c/:id"
      ],
      "target": "/c/:id"
    }
  ],
  "topFeeds": [
    {
      "description": "My name is Grant Sanderson. Videos here cover a variety of topics in math, or adjacent fields like physics and CS, all with an emphasis on visualizing the core ideas. The goal is to use animation to help elucidate and motivate otherwise tricky topics, and for difficult problems to be made simple with changes in perspective. For more information, other projects, FAQs, and inquiries see the website: https://www.3blue1brown.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "83922899515574272",
      "image": "https://yt3.googleusercontent.com/ytc/AIdro_nFzZFPLxPZRHcE3SSwzdrbuWqfoWYwLAu0_2iO6blQYAU=s900-c-k-c0x00ffffff-no-rj",
      "ownerUserId": null,
      "siteUrl": "https://www.youtube.com/c/3blue1brown",
      "title": "3blue1brown - YouTube",
      "type": "feed",
      "url": "rsshub://youtube/c/3blue1brown"
    },
    {
      "description": "Lex Fridman Podcast and other videos. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69248136853592064",
      "image": "https://yt3.googleusercontent.com/ytc/AIdro_ljfMy9kUR1PH9VRf-XsTsPqFMgORC_zodOQVEAm4hx36lC=s900-c-k-c0x00ffffff-no-rj",
      "ownerUserId": null,
      "siteUrl": "https://www.youtube.com/c/lexfridman",
      "title": "lexfridman - YouTube",
      "type": "feed",
      "url": "rsshub://youtube/c/lexfridman"
    }
  ]
}
```
