# Huggingface - Community Articles

## Coverage
`index-only`

## Route
- Namespace: `huggingface`
- Namespace Name: `Huggingface`
- Route Path: `/huggingface/blog-community/:sort?`
- Route Name: `Community Articles`
- Example: `/huggingface/blog-community`
- URL: `huggingface.co/blog/community`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `yuguorui`
- Source Location: `blog-community.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `sort`: {"default": "trending", "description": "Sort by trending or recent", "options": [{"label": "Trending", "value": "trending"}, {"label": "Recent", "value": "recent"}]}


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
  - `huggingface.co/blog/community`
  - `huggingface.co/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/huggingface/blog-community",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 75,
  "location": "blog-community.ts",
  "maintainers": [
    "yuguorui"
  ],
  "name": "Community Articles",
  "parameters": {
    "sort": {
      "default": "trending",
      "description": "Sort by trending or recent",
      "options": [
        {
          "label": "Trending",
          "value": "trending"
        },
        {
          "label": "Recent",
          "value": "recent"
        }
      ]
    }
  },
  "path": "/blog-community/:sort?",
  "radar": [
    {
      "source": [
        "huggingface.co/blog/community",
        "huggingface.co/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Huggingface Community Articles - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "144398027815873536",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://huggingface.co/blog/community",
      "title": "Huggingface Community Articles",
      "type": "feed",
      "url": "rsshub://huggingface/blog-community"
    },
    {
      "description": "Huggingface Community Articles - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "163588196308261888",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://huggingface.co/blog/community",
      "title": "Huggingface Community Articles",
      "type": "feed",
      "url": "rsshub://huggingface/blog-community/trending"
    }
  ],
  "url": "huggingface.co/blog/community"
}
```
