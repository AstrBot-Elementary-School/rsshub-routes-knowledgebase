# The Hindu - Topic

## Coverage
`index-only`

## Route
- Namespace: `thehindu`
- Namespace Name: `The Hindu`
- Route Path: `/thehindu/topic/:topic`
- Route Name: `Topic`
- Example: `/thehindu/topic/rains`
- URL: `thehindu.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: Topic slug, can be found in URL.


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
  - `thehindu.com/topic/:topic`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/thehindu/topic/rains",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 12,
  "location": "topic.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Topic",
  "parameters": {
    "topic": "Topic slug, can be found in URL."
  },
  "path": "/topic/:topic",
  "radar": [
    {
      "source": [
        "thehindu.com/topic/:topic"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Latest Right to Privacy News, Photos, Latest News Headlines about Right to Privacy-The Hindu - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "118671170053553152",
      "image": "https://www.thehindu.com/theme/images/th-online/OG-sections.png",
      "ownerUserId": null,
      "siteUrl": "https://www.thehindu.com/topic/Right_to_Privacy/",
      "title": "Latest Right to Privacy News, Photos, Latest News Headlines about Right to Privacy-The Hindu",
      "type": "feed",
      "url": "rsshub://thehindu/topic/Right_to_Privacy"
    }
  ]
}
```
