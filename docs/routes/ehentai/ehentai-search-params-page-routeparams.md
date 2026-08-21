# E-Hentai - Search

## Coverage
`index-only`

## Route
- Namespace: `ehentai`
- Namespace Name: `E-Hentai`
- Route Path: `/ehentai/search/:params?/:page?/:routeParams?`
- Route Name: `Search`
- Example: `/ehentai/search/f_cats=1021/0/bittorrent=true&embed_thumb=false`
- URL: `_None_`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `yindaheng98, syrinka`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `params`: Search parameters. You can copy the content after `https://e-hentai.org/?`
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
  "example": "/ehentai/search/f_cats=1021/0/bittorrent=true&embed_thumb=false",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 285,
  "location": "search.ts",
  "maintainers": [
    "yindaheng98",
    "syrinka"
  ],
  "name": "Search",
  "parameters": {
    "page": "Page number, set 0 to get latest",
    "params": "Search parameters. You can copy the content after `https://e-hentai.org/?`",
    "routeParams": "Additional parameters, see the table above"
  },
  "path": "/search/:params?/:page?/:routeParams?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "ごさいじ+language:\"chinese\" - E-Hentai Search - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "132859028606370816",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://e-hentai.org/?f_search=%E3%81%94%E3%81%95%E3%81%84%E3%81%98+language:%22chinese%22",
      "title": "ごさいじ+language:\"chinese\" - E-Hentai Search",
      "type": "feed",
      "url": "rsshub://ehentai/search/f_search=%E3%81%94%E3%81%95%E3%81%84%E3%81%98+language%3A%22chinese%22"
    },
    {
      "description": "undefined - E-Hentai Search - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "96502911354921984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://e-hentai.org/?undefined",
      "title": "undefined - E-Hentai Search",
      "type": "feed",
      "url": "rsshub://ehentai/search"
    }
  ]
}
```
