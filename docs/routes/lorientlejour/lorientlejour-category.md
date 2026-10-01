# L'Orient-Le Jour/L'Orient Today - Category

## Coverage
`index-only`

## Route
- Namespace: `lorientlejour`
- Namespace Name: `L'Orient-Le Jour/L'Orient Today`
- Route Path: `/lorientlejour/:category?`
- Route Name: `Category`
- Example: `/lorientlejour/977-lebanon`
- URL: `lorientlejour.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
::: tip
For example, the path for the sites <https://today.lorientlejour.com/section/977-lebanon> and <https://www.lorientlejour.com/rubrique/1-liban> would be /lorientlejour/977-lebanon and /lorientlejour/1-liban respectively.
Multiple categories seperated by '|' is also supported, e.g. /lorientlejour/977-lebanon|1-liban.
:::

## Parameters
- `category`: Category from the last segment of the URL of the corresponding site, see below for more information, /977-Lebanon by default


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `requireConfig`: [{"description": "L'Orient-Le Jour/L'Orient Today Email or Username", "name": "LORIENTLEJOUR_USERNAME", "optional": true}, {"description": "L'Orient-Le Jour/L'Orient Today Password", "name": "LORIENTLEJOUR_PASSWORD", "optional": true}, {"description": "To obtain a token, log into L'Orient-Le Jour/L'Orient Today App and inspect the connection request to find the token parameter from the request URL", "name": "LORIENTLEJOUR_TOKEN", "optional": true}]

## Radar
### Rule 1
- `source`:
  - `www.lorientlejour.com/*/:category`
- `target`: `/:category`
### Rule 2
- `source`:
  - `www.lorientlejour.com`
- `target`: `/1-Liban`
### Rule 3
- `source`:
  - `today.lorientlejour.com/*/:category`
- `target`: `/:category`
### Rule 4
- `source`:
  - `today.lorientlejour.com`
- `target`: `/977-Lebanon`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "::: tip\nFor example, the path for the sites <https://today.lorientlejour.com/section/977-lebanon> and <https://www.lorientlejour.com/rubrique/1-liban> would be /lorientlejour/977-lebanon and /lorientlejour/1-liban respectively.\nMultiple categories seperated by '|' is also supported, e.g. /lorientlejour/977-lebanon|1-liban.\n:::",
  "example": "/lorientlejour/977-lebanon",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "L'Orient-Le Jour/L'Orient Today Email or Username",
        "name": "LORIENTLEJOUR_USERNAME",
        "optional": true
      },
      {
        "description": "L'Orient-Le Jour/L'Orient Today Password",
        "name": "LORIENTLEJOUR_PASSWORD",
        "optional": true
      },
      {
        "description": "To obtain a token, log into L'Orient-Le Jour/L'Orient Today App and inspect the connection request to find the token parameter from the request URL",
        "name": "LORIENTLEJOUR_TOKEN",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10,
  "location": "index.tsx",
  "maintainers": [
    "quiniapiezoelectricity"
  ],
  "name": "Category",
  "parameters": {
    "category": "Category from the last segment of the URL of the corresponding site, see below for more information, /977-Lebanon by default"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.lorientlejour.com/*/:category"
      ],
      "target": "/:category"
    },
    {
      "source": [
        "www.lorientlejour.com"
      ],
      "target": "/1-Liban"
    },
    {
      "source": [
        "today.lorientlejour.com/*/:category"
      ],
      "target": "/:category"
    },
    {
      "source": [
        "today.lorientlejour.com"
      ],
      "target": "/977-Lebanon"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "L'Orient Today - Lebanon - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68949378330868736",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://today.lorientlejour.com/section/977-lebanon",
      "title": "L'Orient Today - Lebanon",
      "type": "feed",
      "url": "rsshub://lorientlejour"
    },
    {
      "description": "L'Orient Today - Lebanon - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67213346383532032",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://today.lorientlejour.com/section/977-lebanon",
      "title": "L'Orient Today - Lebanon",
      "type": "feed",
      "url": "rsshub://lorientlejour/977-lebanon"
    }
  ]
}
```
