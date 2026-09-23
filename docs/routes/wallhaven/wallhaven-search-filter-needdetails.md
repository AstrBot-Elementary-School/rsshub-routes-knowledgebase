# wallhaven - Search

## Coverage
`index-only`

## Route
- Namespace: `wallhaven`
- Namespace Name: `wallhaven`
- Route Path: `/wallhaven/search/:filter?/:needDetails?`
- Route Name: `Search`
- Example: `/wallhaven/search/categories=110&purity=110&sorting=date_added&order=desc`
- URL: `wallhaven.cc/`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `nczitzk, Fatpandac`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
Subscribe pages starting with `https://wallhaven.cc/search`, fill the text after `?` as `filter` in the route. The following is an example:

The text after `?` is `q=id%3A711&sorting=random&ref=fp&seed=8g0dgd` for [Wallpaper Search: #landscape - wallhaven.cc](https://wallhaven.cc/search?q=id%3A711\&sorting=random\&ref=fp\&seed=8g0dgd), so the route is [/wallhaven/q=id%3A711\&sorting=random\&ref=fp\&seed=8g0dgd](https://rsshub.app/wallhaven/q=id%3A711\&sorting=random\&ref=fp\&seed=8g0dgd)
:::

## Parameters
- `filter`: Filter, empty by default
- `needDetails`: Need Details, `true`/`yes` as yes, no by default


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
  - `wallhaven.cc/`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "::: tip\nSubscribe pages starting with `https://wallhaven.cc/search`, fill the text after `?` as `filter` in the route. The following is an example:\n\nThe text after `?` is `q=id%3A711&sorting=random&ref=fp&seed=8g0dgd` for [Wallpaper Search: #landscape - wallhaven.cc](https://wallhaven.cc/search?q=id%3A711\\&sorting=random\\&ref=fp\\&seed=8g0dgd), so the route is [/wallhaven/q=id%3A711\\&sorting=random\\&ref=fp\\&seed=8g0dgd](https://rsshub.app/wallhaven/q=id%3A711\\&sorting=random\\&ref=fp\\&seed=8g0dgd)\n:::",
  "example": "/wallhaven/search/categories=110&purity=110&sorting=date_added&order=desc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 215,
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "Fatpandac"
  ],
  "name": "Search",
  "parameters": {
    "filter": "Filter, empty by default",
    "needDetails": "Need Details, `true`/`yes` as yes, no by default"
  },
  "path": [
    "/search/:filter?/:needDetails?",
    "/:filter?/:needDetails?"
  ],
  "radar": [
    {
      "source": [
        "wallhaven.cc/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Latest Wallpapers - wallhaven.cc - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57995063243930624",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://wallhaven.cc/latest",
      "title": "Latest Wallpapers - wallhaven.cc",
      "type": "feed",
      "url": "rsshub://wallhaven/search"
    },
    {
      "description": "Wallpaper Search: - wallhaven.cc - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41870267217959936",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://wallhaven.cc/search?categories=110&purity=110&sorting=date_added&order=desc",
      "title": "Wallpaper Search: - wallhaven.cc",
      "type": "feed",
      "url": "rsshub://wallhaven/search/categories=110&purity=110&sorting=date_added&order=desc"
    }
  ],
  "url": "wallhaven.cc/"
}
```
