# Ganjing World - posts in a channel

## Coverage
`index-only`

## Route
- Namespace: `ganjingworld`
- Namespace Name: `Ganjing World`
- Route Path: `/ganjingworld/channel/posts/:id`
- Route Name: `posts in a channel`
- Example: `/ganjingworld/channel/posts/1fcahpcut9t3gz4zIvYSJR7qd1cs0c`
- URL: `www.ganjingworld.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `yixiangli2001`
- Source Location: `channel/posts.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Channel ID, can be found in channel url


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
  - `ganjingworld.com/channel/:id`
  - `www.ganjingworld.com/channel/:id`
- `target`: `/channel/posts/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/ganjingworld/channel/posts/1fcahpcut9t3gz4zIvYSJR7qd1cs0c",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "channel/posts.ts",
  "maintainers": [
    "yixiangli2001"
  ],
  "name": "posts in a channel",
  "parameters": {
    "id": "Channel ID, can be found in channel url"
  },
  "path": "/channel/posts/:id",
  "radar": [
    {
      "source": [
        "ganjingworld.com/channel/:id",
        "www.ganjingworld.com/channel/:id"
      ],
      "target": "/channel/posts/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.ganjingworld.com"
}
```
