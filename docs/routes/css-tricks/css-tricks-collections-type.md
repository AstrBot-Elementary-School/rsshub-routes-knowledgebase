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
- `type`: {"description": "Collection Type", "options": [{"label": "Latest CSS Guides", "value": "3"}, {"label": "Fresh From the Almanac", "value": "2"}, {"label": "Classic Tricks", "value": "4"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `title`: `Fresh From the Almanac`
- `source`:
  - `css-tricks.com/`
- `target`: `/collections/2`
### Rule 2
- `title`: `CSS Guides`
- `source`:
  - `css-tricks.com/`
- `target`: `/collections/3`
### Rule 3
- `title`: `Classic Tricks`
- `source`:
  - `css-tricks.com/`
- `target`: `/collections/4`

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
    "type": {
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
        "css-tricks.com/"
      ],
      "target": "/collections/2",
      "title": "Fresh From the Almanac"
    },
    {
      "source": [
        "css-tricks.com/"
      ],
      "target": "/collections/3",
      "title": "CSS Guides"
    },
    {
      "source": [
        "css-tricks.com/"
      ],
      "target": "/collections/4",
      "title": "Classic Tricks"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Properties, selectors, rules, and functions! - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
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
