# FANTUBE - User Posts

## Coverage
`index-only`

## Route
- Namespace: `fantube`
- Namespace Name: `FANTUBE`
- Route Path: `/fantube/r18/creator/:identifier`
- Route Name: `User Posts`
- Example: `/fantube/r18/creator/miyuu`
- URL: `www.fantube.tokyo`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `creator.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `identifier`: User handle


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
  - `www.fantube.tokyo/r18/creator/:identifier`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/fantube/r18/creator/miyuu",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "creator.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "User Posts",
  "parameters": {
    "identifier": "User handle"
  },
  "path": "/r18/creator/:identifier",
  "radar": [
    {
      "source": [
        "www.fantube.tokyo/r18/creator/:identifier"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "勉強中なので色々教えてくださいっ！🐥 - Powered by RSSHub",
      "errorAt": "2025-10-02T05:26:44.136Z",
      "errorMessage": "Authentication failed. Access denied.\n/fantube/r18/creator/miyuu\nCannot read properties of undefined (reading 'slice')\nCannot read properties of undefined (reading 'slice')\n",
      "id": "172884205682714624",
      "image": "https://pub-823015c3ebdd4468bdae83727431c156.r2.dev/d1c44b54-51c6-4e61-afba-6de507a32b7d",
      "ownerUserId": null,
      "siteUrl": "https://www.fantube.tokyo/r18/creator/miyuu",
      "title": "みゆうのプロフィール｜クリエイターページ｜FANTUBE(ファンチューブ)",
      "type": "feed",
      "url": "rsshub://fantube/r18/creator/miyuu"
    }
  ]
}
```
