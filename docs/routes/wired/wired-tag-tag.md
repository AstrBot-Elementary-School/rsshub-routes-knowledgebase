# WIRED - Tags

## Coverage
`index-only`

## Route
- Namespace: `wired`
- Namespace Name: `WIRED`
- Route Path: `/wired/tag/:tag`
- Route Name: `Tags`
- Example: `/wired/tag/facebook`
- URL: `www.wired.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `Naiqus`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tag`: Tag name


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.wired.com/tag/:tag/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/wired/tag/facebook",
  "heat": 196,
  "location": "tag.ts",
  "maintainers": [
    "Naiqus"
  ],
  "name": "Tags",
  "parameters": {
    "tag": "Tag name"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "www.wired.com/tag/:tag/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Artificial Intelligence | Latest News, Photos & Videos | WIRED - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65791385545769984",
      "image": "https://www.wired.com/verso/static/wired-us/assets/logo.svg",
      "ownerUserId": null,
      "siteUrl": "https://www.wired.com/tag/artificial-intelligence/",
      "title": "Artificial Intelligence | Latest News, Photos & Videos | WIRED",
      "type": "feed",
      "url": "rsshub://wired/tag/artificial-intelligence"
    },
    {
      "description": "Find the latest Bitcoin news from WIRED. See related science and technology articles, photos, slideshows and videos. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60143536924270671",
      "image": "https://www.wired.com/verso/static/wired-us/assets/logo.svg",
      "ownerUserId": null,
      "siteUrl": "https://www.wired.com/tag/bitcoin/",
      "title": "Bitcoin | Latest News, Photos & Videos | WIRED",
      "type": "feed",
      "url": "rsshub://wired/tag/bitcoin"
    }
  ]
}
```
