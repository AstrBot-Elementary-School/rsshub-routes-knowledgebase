# E-Hentai - Tag

## Coverage
`index-only`

## Route
- Namespace: `ehentai`
- Namespace Name: `E-Hentai`
- Route Path: `/ehentai/tag/:tag/:page?/:routeParams?`
- Route Name: `Tag`
- Example: `/ehentai/tag/language:chinese/0/bittorrent=true&embed_thumb=false`
- URL: `_None_`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `yindaheng98, syrinka`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tag`: Tag
- `page`: Page number, set 0 to get latest
- `routeParams`: Additional parameters, see the table above


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/ehentai/tag/language:chinese/0/bittorrent=true&embed_thumb=false",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 128,
  "location": "tag.ts",
  "maintainers": [
    "yindaheng98",
    "syrinka"
  ],
  "name": "Tag",
  "parameters": {
    "page": "Page number, set 0 to get latest",
    "routeParams": "Additional parameters, see the table above",
    "tag": "Tag"
  },
  "path": "/tag/:tag/:page?/:routeParams?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "language:chinese - E-Hentai Tag - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "120679993479343104",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://e-hentai.org/tag/language:chinese",
      "title": "language:chinese - E-Hentai Tag",
      "type": "feed",
      "url": "rsshub://ehentai/tag/language:chinese/0/bittorrent=true&embed_thumb=false"
    },
    {
      "description": "language:chinese - E-Hentai Tag - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "76924878996884480",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://e-hentai.org/tag/language:chinese",
      "title": "language:chinese - E-Hentai Tag",
      "type": "feed",
      "url": "rsshub://ehentai/tag/language:chinese/0"
    }
  ]
}
```
