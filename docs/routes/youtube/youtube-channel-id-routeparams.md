# YouTube - Channel with id

## Coverage
`index-only`

## Route
- Namespace: `youtube`
- Namespace Name: `YouTube`
- Route Path: `/youtube/channel/:id/:routeParams?`
- Route Name: `Channel with id`
- Example: `/youtube/channel/UCDwDMPOZfxVV0x_dz0eQ8KQ`
- URL: `youtube.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `DIYgod, pseudoyu`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
::: tip Parameter

| Name         | Description                                                                        | Default |
| ------------ | ---------------------------------------------------------------------------------- | ------- |
| embed        | Whether to embed the video, fill in any value to disable embedding                 | embed   |
| filterShorts | Whether to filter out shorts from the feed, fill in any falsy value to show shorts | true    |

:::

::: tip
YouTube provides official RSS feeds for channels, for instance <https://www.youtube.com/feeds/videos.xml?channel_id=UCDwDMPOZfxVV0x_dz0eQ8KQ>.
:::

## Parameters
- `id`: YouTube channel id
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
  - `www.youtube.com/channel/:id`
- `target`: `/channel/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "description": "::: tip Parameter\n\n| Name         | Description                                                                        | Default |\n| ------------ | ---------------------------------------------------------------------------------- | ------- |\n| embed        | Whether to embed the video, fill in any value to disable embedding                 | embed   |\n| filterShorts | Whether to filter out shorts from the feed, fill in any falsy value to show shorts | true    |\n\n:::\n\n::: tip\nYouTube provides official RSS feeds for channels, for instance <https://www.youtube.com/feeds/videos.xml?channel_id=UCDwDMPOZfxVV0x_dz0eQ8KQ>.\n:::",
  "example": "/youtube/channel/UCDwDMPOZfxVV0x_dz0eQ8KQ",
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
  "heat": 3027,
  "location": "channel.ts",
  "maintainers": [
    "DIYgod",
    "pseudoyu"
  ],
  "name": "Channel with id",
  "parameters": {
    "id": "YouTube channel id",
    "routeParams": "Extra parameters, see the table below"
  },
  "path": "/channel/:id/:routeParams?",
  "radar": [
    {
      "source": [
        "www.youtube.com/channel/:id"
      ],
      "target": "/channel/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "YouTube channel Coding with Lewis - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "143637676052105216",
      "image": "https://yt3.googleusercontent.com/CsruQ_I1lU51KzpO58FHQIpzuQneCdmJOOLsmy_usGKQANxgnJ-cK6kNylwQYhY0LYwVrp3EHQ=s900-c-k-c0x00ffffff-no-rj",
      "ownerUserId": null,
      "siteUrl": "https://www.youtube.com/channel/UCWI-ohtRu8eEeDj93hmUsUQ",
      "title": "Coding with Lewis - YouTube",
      "type": "feed",
      "url": "rsshub://youtube/channel/UCWI-ohtRu8eEeDj93hmUsUQ"
    },
    {
      "description": "YouTube channel 小钟Johnny - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62110731608091648",
      "image": "https://yt3.googleusercontent.com/ytc/AIdro_nLxOCT7qrhIe50CgsatjLIkcALBlBA5b6phRdsYEH9MA=s900-c-k-c0x00ffffff-no-rj",
      "ownerUserId": null,
      "siteUrl": "https://www.youtube.com/channel/UCxr75Ze604OZsLKEAJ4jqAg",
      "title": "小钟Johnny - YouTube",
      "type": "feed",
      "url": "rsshub://youtube/channel/UCxr75Ze604OZsLKEAJ4jqAg"
    }
  ]
}
```
