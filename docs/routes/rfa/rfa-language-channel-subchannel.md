# Radio Free Asia (RFA) 自由亚洲电台 - News

## Coverage
`index-only`

## Route
- Namespace: `rfa`
- Namespace Name: `Radio Free Asia (RFA) 自由亚洲电台`
- Route Path: `/rfa/:language?/:channel?/:subChannel?`
- Route Name: `News`
- Example: `/rfa/english`
- URL: `rfa.org`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `zphw`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Delivers a better experience by supporting parameter specification.

Parameters can be obtained from the official website, for instance:

`https://www.rfa.org/cantonese` corresponds to `/rfa/cantonese`

`https://www.rfa.org/cantonese/htm` corresponds to `/rfa/cantonese/htm`

## Parameters
- `language`: language, English by default
- `channel`: channel
- `subChannel`: subchannel, where applicable


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
    "traditional-media"
  ],
  "description": "Delivers a better experience by supporting parameter specification.\n\nParameters can be obtained from the official website, for instance:\n\n`https://www.rfa.org/cantonese` corresponds to `/rfa/cantonese`\n\n`https://www.rfa.org/cantonese/htm` corresponds to `/rfa/cantonese/htm`",
  "example": "/rfa/english",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 30,
  "location": "index.ts",
  "maintainers": [
    "zphw"
  ],
  "name": "News",
  "parameters": {
    "channel": "channel",
    "language": "language, English by default",
    "subChannel": "subchannel, where applicable"
  },
  "path": "/:language?/:channel?/:subChannel?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "普通话主页 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41511702474276901",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.rfa.org/mandarin/",
      "title": "普通话主页",
      "type": "feed",
      "url": "rsshub://rfa/mandarin"
    },
    {
      "description": "Radio Free Asia - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60960710409964544",
      "image": "https://cloudfront-us-east-1.images.arcpublishing.com/radiofreeasia/NG6VSBG6T5FE5G5WNXD66KOHTQ.png",
      "ownerUserId": null,
      "siteUrl": "https://www.rfa.org/english/",
      "title": "Radio Free Asia",
      "type": "feed",
      "url": "rsshub://rfa/english"
    }
  ]
}
```
