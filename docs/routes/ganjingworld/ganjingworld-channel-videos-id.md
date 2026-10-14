# Ganjing World - Videos in a channel

## Coverage
`index-only`

## Route
- Namespace: `ganjingworld`
- Namespace Name: `Ganjing World`
- Route Path: `/ganjingworld/channel/videos/:id`
- Route Name: `Videos in a channel`
- Example: `/ganjingworld/channel/videos/1eiqjdnq7go1OPYtIbLDVMpM61ok0c`
- URL: `www.ganjingworld.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `yixiangli2001`
- Source Location: `channel/videos.ts`
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
- `target`: `/channel/videos/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/ganjingworld/channel/videos/1eiqjdnq7go1OPYtIbLDVMpM61ok0c",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "channel/videos.ts",
  "maintainers": [
    "yixiangli2001"
  ],
  "name": "Videos in a channel",
  "parameters": {
    "id": "Channel ID, can be found in channel url"
  },
  "path": "/channel/videos/:id",
  "radar": [
    {
      "source": [
        "ganjingworld.com/channel/:id",
        "www.ganjingworld.com/channel/:id"
      ],
      "target": "/channel/videos/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.ganjingworld.com"
}
```
