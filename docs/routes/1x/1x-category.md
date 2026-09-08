# 1x.com - Gallery

## Coverage
`index-only`

## Route
- Namespace: `1x`
- Namespace Name: `1x.com`
- Route Path: `/1x/:category{.+}?`
- Route Name: `Gallery`
- Example: `/1x/latest/awarded`
- URL: `1x.com`
- Language: `_None_`
- Categories: `design, picture, popular`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
::: tip
Fill in the field in the path with the part of the corresponding page URL after `https://1x.com/gallery/` or `https://1x.com/photo/`. Here are the examples:

If you subscribe to [Abstract Awarded](https://1x.com/gallery/abstract/awarded), you should fill in the path with the part `abstract/awarded` from the page URL `https://1x.com/gallery/abstract/awarded`. In this case, the route will be [`/1x/abstract/awarded`](https://rsshub.app/1x/abstract/awarded).

If you subscribe to [Wildlife Published](https://1x.com/gallery/wildlife/published), you should fill in the path with the part `wildlife/published` from the page URL `https://1x.com/gallery/wildlife/published`. In this case, the route will be [`/1x/wildlife/published`](https://rsshub.app/1x/wildlife/published).
:::

## Parameters
- `category`: Category, Latest Awarded by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `/gallery/:category*`
  - `/photos/:category*`
- `target`: `/1x/:category`

## Raw JSON
```json
{
  "categories": [
    "design",
    "picture",
    "popular"
  ],
  "description": "::: tip\nFill in the field in the path with the part of the corresponding page URL after `https://1x.com/gallery/` or `https://1x.com/photo/`. Here are the examples:\n\nIf you subscribe to [Abstract Awarded](https://1x.com/gallery/abstract/awarded), you should fill in the path with the part `abstract/awarded` from the page URL `https://1x.com/gallery/abstract/awarded`. In this case, the route will be [`/1x/abstract/awarded`](https://rsshub.app/1x/abstract/awarded).\n\nIf you subscribe to [Wildlife Published](https://1x.com/gallery/wildlife/published), you should fill in the path with the part `wildlife/published` from the page URL `https://1x.com/gallery/wildlife/published`. In this case, the route will be [`/1x/wildlife/published`](https://rsshub.app/1x/wildlife/published).\n:::",
  "example": "/1x/latest/awarded",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 51352,
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Gallery",
  "parameters": {
    "category": "Category, Latest Awarded by default"
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "/gallery/:category*",
        "/photos/:category*"
      ],
      "target": "/1x/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "1x.com is the world's biggest curated photo gallery online. Each photo is selected by professional curators. 1x.com • In Pursuit of the Sublime - Powered by RSSHub",
      "errorAt": "2026-09-07T10:01:45.018Z",
      "errorMessage": "Failed query: update \"feeds\" set \"url\" = $1, \"title\" = $2, \"description\" = $3, \"site_url\" = $4, \"image\" = $5, \"checked_at\" = $6, \"refresh_enqueued_at\" = $7, \"last_modified_header\" = $8, \"etag_header\" = $9, \"ttl\" = $10, \"error_message\" = $11, \"error_at\" = $12, \"rsshub_route\" = $13, \"rsshub_namespace\" = $14 where (\"feeds\".\"id\" = $15 and (\"feeds\".\"refresh_enqueued_at\" is null or \"feeds\".\"refresh_enqueued_at\" < $16)) returning \"checked_at\"\nparams: rsshub://1x,1x.com • In Pursuit of the Sublime,1x.com is the world's biggest curated photo gallery online. Each photo is selected by professional curators. 1x.com • In Pursuit of the Sublime - Powered by RSSHub,https://1x.com/gallery/latest/awarded,https://1x.com/assets/img/1x-logo-1.png,2026-09-07T10:00:36.957Z,2026-09-07T10:00:31.557Z,Fri, 04 Sep 2026 07:22:19 GMT,W/\"44cc-bguVdq5YcKXkkvx77OE45qh3vaE\",60,,,/1x/:category{.+}?,1x,59581478522199040,2026-09-07T10:00:31.557Z",
      "id": "59581478522199040",
      "image": "https://1x.com/assets/img/1x-logo-1.png",
      "ownerUserId": null,
      "siteUrl": "https://1x.com/gallery/latest/awarded",
      "title": "1x.com • In Pursuit of the Sublime",
      "type": "feed",
      "url": "rsshub://1x"
    },
    {
      "description": "1x.com is the world's biggest curated photo gallery online. Each photo is selected by professional curators. 1x.com • In Pursuit of the Sublime - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41375451836487680",
      "image": "https://1x.com/assets/img/1x-logo-1.png",
      "ownerUserId": null,
      "siteUrl": "https://1x.com/gallery/latest/awarded",
      "title": "1x.com • In Pursuit of the Sublime",
      "type": "feed",
      "url": "rsshub://1x/latest/awarded"
    }
  ],
  "url": "1x.com"
}
```
