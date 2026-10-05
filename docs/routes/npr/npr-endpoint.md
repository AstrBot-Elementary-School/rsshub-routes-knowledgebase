# NPR (National Public Radio) - News

## Coverage
`index-only`

## Route
- Namespace: `npr`
- Namespace Name: `NPR (National Public Radio)`
- Route Path: `/npr/:endpoint?`
- Route Name: `News`
- Example: `/npr/1001`
- URL: `npr.org`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `bennyyip`
- Source Location: `full.ts`
- Source Module: `_None_`

## Description
Provide full article RSS for CBC topics.

## Parameters
- `endpoint`: Channel ID, can be found in Official RSS URL, `1001` by default


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
  "description": "Provide full article RSS for CBC topics.",
  "example": "/npr/1001",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 68,
  "location": "full.ts",
  "maintainers": [
    "bennyyip"
  ],
  "name": "News",
  "parameters": {
    "endpoint": "Channel ID, can be found in Official RSS URL, `1001` by default"
  },
  "path": "/:endpoint?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "NPR news, audio, and podcasts. Coverage of breaking stories, national and world news, politics, business, science, technology, and extended coverage of major national and world events. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66080131439415296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.npr.org/templates/story/story.php?storyId=1001",
      "title": "NPR Topics: News",
      "type": "feed",
      "url": "rsshub://npr/1001"
    },
    {
      "description": "NPR news, audio, and podcasts. Coverage of breaking stories, national and world news, politics, business, science, technology, and extended coverage of major national and world events. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "152995209828799488",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.npr.org/templates/story/story.php?storyId=1001",
      "title": "NPR Topics: News",
      "type": "feed",
      "url": "rsshub://npr"
    }
  ]
}
```
