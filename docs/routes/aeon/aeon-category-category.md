# AEON - Categories

## Coverage
`index-only`

## Route
- Namespace: `aeon`
- Namespace Name: `AEON`
- Route Path: `/aeon/category/:category`
- Route Name: `Categories`
- Example: `/aeon/category/philosophy`
- URL: `aeon.co`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `emdoe`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"description": "Category", "options": [{"label": "Philosophy", "value": "philosophy"}, {"label": "Science", "value": "science"}, {"label": "Psychology", "value": "psychology"}, {"label": "Society", "value": "society"}, {"label": "Culture", "value": "culture"}]}


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
  - `aeon.co/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/aeon/category/philosophy",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 490,
  "location": "category.ts",
  "maintainers": [
    "emdoe"
  ],
  "name": "Categories",
  "parameters": {
    "category": {
      "description": "Category",
      "options": [
        {
          "label": "Philosophy",
          "value": "philosophy"
        },
        {
          "label": "Science",
          "value": "science"
        },
        {
          "label": "Psychology",
          "value": "psychology"
        },
        {
          "label": "Society",
          "value": "society"
        },
        {
          "label": "Culture",
          "value": "culture"
        }
      ]
    }
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "aeon.co/:category"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Science Essays from Aeon. World-leading scientists and science writers explore topics from theories of evolution to theories of consciousness, quantum physics to deep time, chemistry to cosmology. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84293189028533248",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://aeon.co/category/science",
      "title": "AEON | Science",
      "type": "feed",
      "url": "rsshub://aeon/category/science"
    },
    {
      "description": "Philosophy Essays from Aeon. World-leading thinkers explore life’s big questions and the history of ideas from Socrates to Simone de Beauvoir, political philosophy to philosophy of mind, the Western canon and the non-Western world. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71782163523746816",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://aeon.co/category/philosophy",
      "title": "AEON | Philosophy",
      "type": "feed",
      "url": "rsshub://aeon/category/philosophy"
    }
  ]
}
```
