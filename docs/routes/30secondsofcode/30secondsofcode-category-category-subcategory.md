# 30 Seconds of code - Category and Subcategory

## Coverage
`index-only`

## Route
- Namespace: `30secondsofcode`
- Namespace Name: `30 Seconds of code`
- Route Path: `/30secondsofcode/category/:category?/:subCategory?`
- Route Name: `Category and Subcategory`
- Example: `/30secondsofcode/category/css/interactivity`
- URL: `www.30secondsofcode.org`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `Rjnishant530`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"description": "Main Category. For Complete list visit site \"https://www.30secondsofcode.org/collections/p/1/\"", "options": [{"label": "Javascript", "value": "js"}, {"label": "CSS", "value": "css"}, {"label": "JavaScript Algorithms", "value": "algorithm"}, {"label": "React", "value": "react"}]}
- `subCategory`: {"description": "Filter within Category. Visit Individual Category site for subCategories"}


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
  - `30secondsofcode.org/:category/:subCategory/`
  - `30secondsofcode.org/:category/`
- `target`: `/category/:category/:subCategory`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/30secondsofcode/category/css/interactivity",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 11,
  "location": "category.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "Category and Subcategory",
  "parameters": {
    "category": {
      "description": "Main Category. For Complete list visit site \"https://www.30secondsofcode.org/collections/p/1/\"",
      "options": [
        {
          "label": "Javascript",
          "value": "js"
        },
        {
          "label": "CSS",
          "value": "css"
        },
        {
          "label": "JavaScript Algorithms",
          "value": "algorithm"
        },
        {
          "label": "React",
          "value": "react"
        }
      ]
    },
    "subCategory": {
      "description": "Filter within Category. Visit Individual Category site for subCategories"
    }
  },
  "path": "/category/:category?/:subCategory?",
  "radar": [
    {
      "source": [
        "30secondsofcode.org/:category/:subCategory/",
        "30secondsofcode.org/:category/"
      ],
      "target": "/category/:category/:subCategory"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Browse articles by collection or check out the top picks and latest content below. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "156154806161232896",
      "image": "https://www.30secondsofcode.org/assets/splash/work-sunrise-600.webp",
      "ownerUserId": null,
      "siteUrl": "https://www.30secondsofcode.org/",
      "title": "RSSHub",
      "type": "feed",
      "url": "rsshub://30secondsofcode/category"
    },
    {
      "description": "The JavaScript article collection contains a wide variety of ES6 helper functions. It includes helpers for dealing with primitives, arrays and objects, as well as algorithms, DOM manipulation functions and Node.js utilities. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "98941576365355008",
      "image": "https://www.30secondsofcode.org/assets/splash/laptop-plant-600.webp",
      "ownerUserId": null,
      "siteUrl": "https://www.30secondsofcode.org/",
      "title": "JavaScript Articles",
      "type": "feed",
      "url": "rsshub://30secondsofcode/category/js"
    }
  ]
}
```
