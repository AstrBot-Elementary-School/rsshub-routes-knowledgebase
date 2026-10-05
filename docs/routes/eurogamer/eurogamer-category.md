# Eurogamer - Articles

## Coverage
`index-only`

## Route
- Namespace: `eurogamer`
- Namespace Name: `Eurogamer`
- Route Path: `/eurogamer/:category?`
- Route Name: `Articles`
- Example: `/eurogamer`
- URL: `www.eurogamer.net/latest`
- Language: `_None_`
- Categories: `game`
- Maintainers: `mcdp-adk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Eurogamer's official RSS feeds only include excerpts. This route fetches the full article body from each article page.

## Parameters
- `category`: {"default": "", "description": "Article type. Omit or use `latest` for the latest mix.", "options": [{"label": "Latest", "value": "latest"}, {"label": "blogs", "value": "blogs"}, {"label": "competitions", "value": "competitions"}, {"label": "deals", "value": "deals"}, {"label": "features", "value": "features"}, {"label": "guides", "value": "guides"}, {"label": "interviews", "value": "interviews"}, {"label": "news", "value": "news"}, {"label": "opinions", "value": "opinions"}, {"label": "podcasts", "value": "podcasts"}, {"label": "previews", "value": "previews"}, {"label": "reviews", "value": "reviews"}, {"label": "videos", "value": "videos"}]}


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
  - `www.eurogamer.net/latest`
- `target`: `/`
### Rule 2
- `source`:
  - `www.eurogamer.net/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "Eurogamer's official RSS feeds only include excerpts. This route fetches the full article body from each article page.",
  "example": "/eurogamer",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "mcdp-adk"
  ],
  "name": "Articles",
  "parameters": {
    "category": {
      "default": "",
      "description": "Article type. Omit or use `latest` for the latest mix.",
      "options": [
        {
          "label": "Latest",
          "value": "latest"
        },
        {
          "label": "blogs",
          "value": "blogs"
        },
        {
          "label": "competitions",
          "value": "competitions"
        },
        {
          "label": "deals",
          "value": "deals"
        },
        {
          "label": "features",
          "value": "features"
        },
        {
          "label": "guides",
          "value": "guides"
        },
        {
          "label": "interviews",
          "value": "interviews"
        },
        {
          "label": "news",
          "value": "news"
        },
        {
          "label": "opinions",
          "value": "opinions"
        },
        {
          "label": "podcasts",
          "value": "podcasts"
        },
        {
          "label": "previews",
          "value": "previews"
        },
        {
          "label": "reviews",
          "value": "reviews"
        },
        {
          "label": "videos",
          "value": "videos"
        }
      ]
    }
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.eurogamer.net/latest"
      ],
      "target": "/"
    },
    {
      "source": [
        "www.eurogamer.net/:category"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.eurogamer.net/latest",
  "view": 0
}
```
