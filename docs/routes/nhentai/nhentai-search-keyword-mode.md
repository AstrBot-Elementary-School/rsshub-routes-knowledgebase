# nhentai - Advanced Search

## Coverage
`index-only`

## Route
- Namespace: `nhentai`
- Namespace Name: `nhentai`
- Route Path: `/nhentai/search/:keyword/:mode?`
- Route Name: `Advanced Search`
- Example: `/nhentai/search/language%3Ajapanese+-scat+-yaoi+-guro+-"mosaic+censorship"`
- URL: `nhentai.net`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `MegrezZhu, hoilc, pseudoyu`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: Keywords for search. You can copy the content after `q=` after searching on the original website, or you can enter it directly. See the [official website](https://nhentai.net/info/) for details
- `mode`: mode, `simple` to only show cover, `detail` to show all pages, `torrent` to include Magnet URI, need login, refer to [Route-specific Configurations](https://docs.rsshub.app/deploy/config#route-specific-configurations), default to `simple`


## Features
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: true
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `nhentai.net/:key/:keyword`
- `target`: `/:key/:keyword`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/nhentai/search/language%3Ajapanese+-scat+-yaoi+-guro+-\"mosaic+censorship\"",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requirePuppeteer": false,
    "supportBT": true
  },
  "heat": 179,
  "location": "search.ts",
  "maintainers": [
    "MegrezZhu",
    "hoilc",
    "pseudoyu"
  ],
  "name": "Advanced Search",
  "parameters": {
    "keyword": "Keywords for search. You can copy the content after `q=` after searching on the original website, or you can enter it directly. See the [official website](https://nhentai.net/info/) for details",
    "mode": "mode, `simple` to only show cover, `detail` to show all pages, `torrent` to include Magnet URI, need login, refer to [Route-specific Configurations](https://docs.rsshub.app/deploy/config#route-specific-configurations), default to `simple`"
  },
  "path": "/search/:keyword/:mode?",
  "radar": [
    {
      "source": [
        "nhentai.net/:key/:keyword"
      ],
      "target": "/:key/:keyword"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "nhentai - search - chinese - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65322834478863360",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nhentai.net/search/?q=chinese",
      "title": "nhentai - search - chinese",
      "type": "feed",
      "url": "rsshub://nhentai/search/chinese"
    },
    {
      "description": "nhentai - search - chinese+stockings - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "54875188593719296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nhentai.net/search/?q=chinese+stockings",
      "title": "nhentai - search - chinese+stockings",
      "type": "feed",
      "url": "rsshub://nhentai/search/chinese+stockings"
    }
  ]
}
```
