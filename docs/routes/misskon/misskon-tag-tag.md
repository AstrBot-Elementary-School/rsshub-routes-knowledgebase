# MissKON - Tag

## Coverage
`index-only`

## Route
- Namespace: `misskon`
- Namespace Name: `MissKON`
- Route Path: `/misskon/tag/:tag`
- Route Name: `Tag`
- Example: `/misskon/tag/cosplay`
- URL: `misskon.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `Urabartin`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tag`: Any tag that exists in MissKon


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `misskon.com/tag/:tag/`
- `target`: `/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/misskon/tag/cosplay",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 918,
  "location": "tag.ts",
  "maintainers": [
    "Urabartin"
  ],
  "name": "Tag",
  "parameters": {
    "tag": "Any tag that exists in MissKon"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "misskon.com/tag/:tag/"
      ],
      "target": "/tag/:tag"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Collection of hot photos and videos of Asian cosplayers. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70321443240539136",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://misskon.com/tag/cosplay/",
      "title": "MissKON - Cosplay",
      "type": "feed",
      "url": "rsshub://misskon/tag/cosplay"
    },
    {
      "description": "We invite you to view and download the <strong>LegBaby</strong> (美腿宝贝) photo sets completely free with very high quality! These photo sets were taken by professional photographers with the participation of Chinese beauties. As the name suggests, the shooting angles mostly focus on the extremely sexy long legs of the models! - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "75542982493503488",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://misskon.com/tag/legbaby/",
      "title": "MissKON - LegBaby",
      "type": "feed",
      "url": "rsshub://misskon/tag/legbaby"
    }
  ]
}
```
