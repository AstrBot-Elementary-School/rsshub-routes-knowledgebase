# Pixabay - Search

## Coverage
`index-only`

## Route
- Namespace: `pixabay`
- Namespace Name: `Pixabay`
- Route Path: `/pixabay/search/:q/:order?`
- Route Name: `Search`
- Example: `/pixabay/search/cat`
- URL: `pixabay.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `TonyRL`
- Source Location: `search.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `q`: Search term
- `order`: {"default": "latest", "description": "Order", "options": [{"label": "popular", "value": "popular"}, {"label": "latest", "value": "latest"}]}


## Features
- `requireConfig`: [{"description": "", "name": "PIXABAY_KEY", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `pixabay.com/:searchType/search/:q`
- `target`: `/search/:q`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/pixabay/search/cat",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "PIXABAY_KEY",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 220,
  "location": "search.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Search",
  "parameters": {
    "order": {
      "default": "latest",
      "description": "Order",
      "options": [
        {
          "label": "popular",
          "value": "popular"
        },
        {
          "label": "latest",
          "value": "latest"
        }
      ]
    },
    "q": "Search term"
  },
  "path": "/search/:q/:order?",
  "radar": [
    {
      "source": [
        "pixabay.com/:searchType/search/:q"
      ],
      "target": "/search/:q"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Download & use free nature stock photos in high resolution ✓ New free images everyday ✓ HD to 4K ✓ Best nature pictures for all devices on Pixabay - Powered by RSSHub",
      "errorAt": "2026-08-15T04:43:17.953Z",
      "errorMessage": "200 ",
      "id": "64636062770488320",
      "image": "https://pixabay.com/apple-touch-icon.png",
      "ownerUserId": null,
      "siteUrl": "https://pixabay.com/images/search/nature/?order=latest",
      "title": "Search nature - Pixabay",
      "type": "feed",
      "url": "rsshub://pixabay/search/nature/latest"
    },
    {
      "description": "Download & use free nature stock photos in high resolution ✓ New free images everyday ✓ HD to 4K ✓ Best nature pictures for all devices on Pixabay - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72900839685521408",
      "image": "https://pixabay.com/apple-touch-icon.png",
      "ownerUserId": null,
      "siteUrl": "https://pixabay.com/images/search/cat/?order=latest",
      "title": "Search cat - Pixabay",
      "type": "feed",
      "url": "rsshub://pixabay/search/cat/latest"
    }
  ],
  "view": 2
}
```
