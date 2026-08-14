# National Geographic - Daily Photo

## Coverage
`index-only`

## Route
- Namespace: `natgeo`
- Namespace Name: `National Geographic`
- Route Path: `/natgeo/dailyphoto`
- Route Name: `Daily Photo`
- Example: `/natgeo/dailyphoto`
- URL: `nationalgeographic.com/photo-of-the-day/*`
- Language: `_None_`
- Categories: `picture, popular`
- Maintainers: `LogicJake, OrangeEd1t, TonyRL, pseudoyu`
- Source Location: `dailyphoto.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `nationalgeographic.com/photo-of-the-day/*`
  - `nationalgeographic.com/`

## Raw JSON
```json
{
  "categories": [
    "picture",
    "popular"
  ],
  "example": "/natgeo/dailyphoto",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2577,
  "location": "dailyphoto.tsx",
  "maintainers": [
    "LogicJake",
    "OrangeEd1t",
    "TonyRL",
    "pseudoyu"
  ],
  "name": "Daily Photo",
  "parameters": {},
  "path": "/dailyphoto",
  "radar": [
    {
      "source": [
        "nationalgeographic.com/photo-of-the-day/*",
        "nationalgeographic.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Nat Geo Photo of the Day - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41699925856588800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nationalgeographic.com/photo-of-the-day",
      "title": "Nat Geo Photo of the Day",
      "type": "feed",
      "url": "rsshub://natgeo/dailyphoto"
    }
  ],
  "url": "nationalgeographic.com/photo-of-the-day/*",
  "view": 2
}
```
