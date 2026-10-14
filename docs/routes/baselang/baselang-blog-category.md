# BaseLang - Blog

## Coverage
`index-only`

## Route
- Namespace: `baselang`
- Namespace Name: `BaseLang`
- Route Path: `/baselang/blog/:category?`
- Route Name: `Blog`
- Example: `/baselang/blog`
- URL: `_None_`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `johan456789`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"description": "Optional category filter", "options": [{"label": "advanced-grammar", "value": "advanced-grammar"}, {"label": "basic-grammar", "value": "basic-grammar"}, {"label": "company", "value": "company"}, {"label": "confidence", "value": "confidence"}, {"label": "humor", "value": "humor"}, {"label": "medellin", "value": "medellin"}, {"label": "motivation", "value": "motivation"}, {"label": "pronunciation", "value": "pronunciation"}, {"label": "study-tips", "value": "study-tips"}, {"label": "success-stories", "value": "success-stories"}, {"label": "travel", "value": "travel"}, {"label": "uncategorized", "value": "uncategorized"}, {"label": "vocabulary", "value": "vocabulary"}]}


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
  - `baselang.com/blog`
  - `baselang.com/blog/:category`
- `target`: `/blog/:category`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/baselang/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "index.ts",
  "maintainers": [
    "johan456789"
  ],
  "name": "Blog",
  "parameters": {
    "category": {
      "description": "Optional category filter",
      "options": [
        {
          "label": "advanced-grammar",
          "value": "advanced-grammar"
        },
        {
          "label": "basic-grammar",
          "value": "basic-grammar"
        },
        {
          "label": "company",
          "value": "company"
        },
        {
          "label": "confidence",
          "value": "confidence"
        },
        {
          "label": "humor",
          "value": "humor"
        },
        {
          "label": "medellin",
          "value": "medellin"
        },
        {
          "label": "motivation",
          "value": "motivation"
        },
        {
          "label": "pronunciation",
          "value": "pronunciation"
        },
        {
          "label": "study-tips",
          "value": "study-tips"
        },
        {
          "label": "success-stories",
          "value": "success-stories"
        },
        {
          "label": "travel",
          "value": "travel"
        },
        {
          "label": "uncategorized",
          "value": "uncategorized"
        },
        {
          "label": "vocabulary",
          "value": "vocabulary"
        }
      ]
    }
  },
  "path": "/blog/:category?",
  "radar": [
    {
      "source": [
        "baselang.com/blog",
        "baselang.com/blog/:category"
      ],
      "target": "/blog/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "BaseLang Blog - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "193955733115727872",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://baselang.com/blog/",
      "title": "BaseLang Blog",
      "type": "feed",
      "url": "rsshub://baselang/blog"
    }
  ]
}
```
