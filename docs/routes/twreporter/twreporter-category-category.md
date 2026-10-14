# 報導者 - 分類

## Coverage
`index-only`

## Route
- Namespace: `twreporter`
- Namespace Name: `報導者`
- Route Path: `/twreporter/category/:category`
- Route Name: `分類`
- Example: `/twreporter/category/world`
- URL: `twreporter.org/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `emdoe`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category


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
  - `twreporter.org/:category`
### Rule 2
- `source`:
  - `twreporter.org/categories/world`
- `target`: `/category/world`
### Rule 3
- `source`:
  - `twreporter.org/categories/humanrights`
- `target`: `/category/humanrights`
### Rule 4
- `source`:
  - `twreporter.org/categories/politics-and-society`
- `target`: `/category/politics_and_society`
### Rule 5
- `source`:
  - `twreporter.org/categories/health`
- `target`: `/category/health`
### Rule 6
- `source`:
  - `twreporter.org/categories/environment`
- `target`: `/category/environment`
### Rule 7
- `source`:
  - `twreporter.org/categories/econ`
- `target`: `/category/econ`
### Rule 8
- `source`:
  - `twreporter.org/categories/culture`
- `target`: `/category/culture`
### Rule 9
- `source`:
  - `twreporter.org/categories/education`
- `target`: `/category/education`
### Rule 10
- `source`:
  - `twreporter.org/categories/podcast`
- `target`: `/category/podcast`
### Rule 11
- `source`:
  - `twreporter.org/categories/opinion`
- `target`: `/category/opinion`
### Rule 12
- `source`:
  - `twreporter.org/categories/photography`
- `target`: `/category/photos_section`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/twreporter/category/world",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 16,
  "location": "category.ts",
  "maintainers": [
    "emdoe"
  ],
  "name": "分類",
  "parameters": {
    "category": "Category"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "twreporter.org/:category"
      ]
    },
    {
      "source": [
        "twreporter.org/categories/world"
      ],
      "target": "/category/world"
    },
    {
      "source": [
        "twreporter.org/categories/humanrights"
      ],
      "target": "/category/humanrights"
    },
    {
      "source": [
        "twreporter.org/categories/politics-and-society"
      ],
      "target": "/category/politics_and_society"
    },
    {
      "source": [
        "twreporter.org/categories/health"
      ],
      "target": "/category/health"
    },
    {
      "source": [
        "twreporter.org/categories/environment"
      ],
      "target": "/category/environment"
    },
    {
      "source": [
        "twreporter.org/categories/econ"
      ],
      "target": "/category/econ"
    },
    {
      "source": [
        "twreporter.org/categories/culture"
      ],
      "target": "/category/culture"
    },
    {
      "source": [
        "twreporter.org/categories/education"
      ],
      "target": "/category/education"
    },
    {
      "source": [
        "twreporter.org/categories/podcast"
      ],
      "target": "/category/podcast"
    },
    {
      "source": [
        "twreporter.org/categories/opinion"
      ],
      "target": "/category/opinion"
    },
    {
      "source": [
        "twreporter.org/categories/photography"
      ],
      "target": "/category/photos_section"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "報導者 | 經濟產業 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "86341038400596992",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.twreporter.org/categories/econ",
      "title": "報導者 | 經濟產業",
      "type": "feed",
      "url": "rsshub://twreporter/category/econ"
    },
    {
      "description": "報導者 | 國際兩岸 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "81748915929398272",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.twreporter.org/categories/world",
      "title": "報導者 | 國際兩岸",
      "type": "feed",
      "url": "rsshub://twreporter/category/world"
    }
  ],
  "url": "twreporter.org/"
}
```
