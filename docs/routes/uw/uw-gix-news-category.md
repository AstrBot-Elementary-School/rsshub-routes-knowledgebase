# University of Washington - Global Innovation Exchange News

## Coverage
`index-only`

## Route
- Namespace: `uw`
- Namespace Name: `University of Washington`
- Route Path: `/uw/gix/news/:category`
- Route Name: `Global Innovation Exchange News`
- Example: `/uw/gix/news/blog`
- URL: `gix.uw.edu`
- Language: `_None_`
- Categories: `university`
- Maintainers: `dykderrick`
- Source Location: `gix/news.ts`
- Source Module: `_None_`

## Description
| Blog | In The News |
| ---- | ----------- |
| blog | inthenews   |

## Parameters
- `category`: Blog Type


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
  - `gixnetwork.org/news/:category`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| Blog | In The News |\n| ---- | ----------- |\n| blog | inthenews   |",
  "example": "/uw/gix/news/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "gix/news.ts",
  "maintainers": [
    "dykderrick"
  ],
  "name": "Global Innovation Exchange News",
  "parameters": {
    "category": "Blog Type"
  },
  "path": "/gix/news/:category",
  "radar": [
    {
      "source": [
        "gixnetwork.org/news/:category"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
