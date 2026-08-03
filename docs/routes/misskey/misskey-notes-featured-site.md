# Misskey - Featured Notes

## Coverage
`index-only`

## Route
- Namespace: `misskey`
- Namespace Name: `Misskey`
- Route Path: `/misskey/notes/featured/:site`
- Route Name: `Featured Notes`
- Example: `/misskey/notes/featured/misskey.io`
- URL: `misskey.io`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Misaka13514`
- Source Location: `featured-notes.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `site`: instance address, domain only, without `http://` or `https://` protocol header


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
    "social-media"
  ],
  "example": "/misskey/notes/featured/misskey.io",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "featured-notes.ts",
  "maintainers": [
    "Misaka13514"
  ],
  "name": "Featured Notes",
  "parameters": {
    "site": "instance address, domain only, without `http://` or `https://` protocol header"
  },
  "path": "/notes/featured/:site",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Featured Notes on misskey.io - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61382857498390528",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://misskey.io/explore",
      "title": "Featured Notes on misskey.io",
      "type": "feed",
      "url": "rsshub://misskey/notes/featured/misskey.io"
    }
  ],
  "view": 1
}
```
