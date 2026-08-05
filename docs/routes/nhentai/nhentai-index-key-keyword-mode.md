# nhentai - Filter

## Coverage
`index-only`

## Route
- Namespace: `nhentai`
- Namespace Name: `nhentai`
- Route Path: `/nhentai/index/:key/:keyword/:mode?`
- Route Name: `Filter`
- Example: `/nhentai/index/language/chinese`
- URL: `nhentai.net`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `MegrezZhu, hoilc, pseudoyu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `key`: Filter term, can be: `parody`, `character`, `tag`, `artist`, `group`, `language` or `category`
- `keyword`: Filter value
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
- `target`: `/index/:key/:keyword`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/nhentai/index/language/chinese",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requirePuppeteer": false,
    "supportBT": true
  },
  "heat": 96,
  "location": "index.ts",
  "maintainers": [
    "MegrezZhu",
    "hoilc",
    "pseudoyu"
  ],
  "name": "Filter",
  "parameters": {
    "key": "Filter term, can be: `parody`, `character`, `tag`, `artist`, `group`, `language` or `category`",
    "keyword": "Filter value",
    "mode": "mode, `simple` to only show cover, `detail` to show all pages, `torrent` to include Magnet URI, need login, refer to [Route-specific Configurations](https://docs.rsshub.app/deploy/config#route-specific-configurations), default to `simple`"
  },
  "path": "/index/:key/:keyword/:mode?",
  "radar": [
    {
      "source": [
        "nhentai.net/:key/:keyword"
      ],
      "target": "/index/:key/:keyword"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "hentai - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56236591640943616",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nhentai.net/artist/doji-ro/",
      "title": "nhentai - artist - doji-ro",
      "type": "feed",
      "url": "rsshub://nhentai/index/artist/doji-ro"
    },
    {
      "description": "hentai - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55635543915975680",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nhentai.net/language/chinese/",
      "title": "nhentai - language - chinese",
      "type": "feed",
      "url": "rsshub://nhentai/index/language/chinese/detail"
    }
  ]
}
```
