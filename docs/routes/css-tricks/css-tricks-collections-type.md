# CSS-Tricks - CSS Guides

## Coverage
`index-only`

## Route
- Namespace: `css-tricks`
- Namespace Name: `CSS-Tricks`
- Route Path: `/css-tricks/collections/:type`
- Route Name: `CSS Guides`
- Example: `/css-tricks/collections/2`
- URL: `css-tricks.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `Rjnishant530`
- Source Location: `collections.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"description": "Collection Type", "options": [{"label": "Latest CSS Guides", "value": "3"}, {"label": "Fresh From the Almanac", "value": "2"}, {"label": "Classic Tricks", "value": "4"}]}


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
  - `css-tricks.com`
- `target`: `/collections/:type`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/css-tricks/collections/2",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "collections.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "CSS Guides",
  "parameters": {
    "category": {
      "description": "Collection Type",
      "options": [
        {
          "label": "Latest CSS Guides",
          "value": "3"
        },
        {
          "label": "Fresh From the Almanac",
          "value": "2"
        },
        {
          "label": "Classic Tricks",
          "value": "4"
        }
      ]
    }
  },
  "path": "/collections/:type",
  "radar": [
    {
      "source": [
        "css-tricks.com"
      ],
      "target": "/collections/:type"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Properties, selectors, rules, and functions! - Powered by RSSHub",
      "errorAt": "2026-07-07T22:13:39.797Z",
      "errorMessage": "[GET] \"https://css-tricks.com/wp-json/wp/v2/pages?include=394713,394732,394739,393611,393625,393615,393630,386953,386948&_embed&per_page=9\": 401 Unauthorized\n",
      "id": "195959369333206016",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://css-tricks.com/",
      "title": "Fresh From the Almanac",
      "type": "feed",
      "url": "rsshub://css-tricks/collections/2"
    }
  ],
  "view": 0
}
```
