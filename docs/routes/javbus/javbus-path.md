# JavBus - Works

## Coverage
`index-only`

## Route
- Namespace: `javbus`
- Namespace Name: `JavBus`
- Route Path: `/javbus/:path{.+}?`
- Route Name: `Works`
- Example: `/javbus/star/rwt`
- URL: `www.javbus.com`
- Language: `_None_`
- Categories: `multimedia, popular`
- Maintainers: `MegrezZhu, CoderTonyChan, nczitzk, Felix2yu`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `path`: {"description": "Any path of list page on javbus"}


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.javbus.com/:path*`
- `target`: `/:path`

## Raw JSON
```json
{
  "categories": [
    "multimedia",
    "popular"
  ],
  "example": "/javbus/star/rwt",
  "features": {
    "nsfw": true
  },
  "heat": 13234,
  "location": "index.tsx",
  "maintainers": [
    "MegrezZhu",
    "CoderTonyChan",
    "nczitzk",
    "Felix2yu"
  ],
  "name": "Works",
  "parameters": {
    "path": {
      "description": "Any path of list page on javbus"
    }
  },
  "path": "/:path{.+}?",
  "radar": [
    {
      "source": [
        "www.javbus.com/:path*"
      ],
      "target": "/:path"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "JavBus - 日本成人影片資料庫 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42521270808612884",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.javbus.com/",
      "title": "JavBus - 日本成人影片資料庫",
      "type": "feed",
      "url": "rsshub://javbus"
    },
    {
      "description": "JavBus - 河北彩花 - 女優 - 影片 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41147805276726357",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.javbus.com/star/sl1",
      "title": "JavBus - 河北彩花 - 女優 - 影片",
      "type": "feed",
      "url": "rsshub://javbus/star/sl1"
    }
  ],
  "url": "www.javbus.com",
  "view": 3
}
```
