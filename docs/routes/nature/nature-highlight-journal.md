# Nature Journal - Research Highlight

## Coverage
`index-only`

## Route
- Namespace: `nature`
- Namespace Name: `Nature Journal`
- Route Path: `/nature/highlight/:journal?`
- Route Name: `Research Highlight`
- Example: `/nature/highlight`
- URL: `nature.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `y9c, TonyRL`
- Source Location: `highlight.ts`
- Source Module: `_None_`

## Description
::: warning
Only some journals are supported.
:::

## Parameters
- `journal`: short name for a journal, `nature` by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: true

## Radar
### Rule 1
- `source`:
  - `nature.com/:journal/articles`
  - `nature.com/:journal`
  - `nature.com/`
- `target`: `/highlight/:journal`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "::: warning\nOnly some journals are supported.\n:::",
  "example": "/nature/highlight",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "heat": 511,
  "location": "highlight.ts",
  "maintainers": [
    "y9c",
    "TonyRL"
  ],
  "name": "Research Highlight",
  "parameters": {
    "journal": "short name for a journal, `nature` by default"
  },
  "path": "/highlight/:journal?",
  "radar": [
    {
      "source": [
        "nature.com/:journal/articles",
        "nature.com/:journal",
        "nature.com/"
      ],
      "target": "/highlight/:journal"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Browse the archive of articles on Nature - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "121071135298905088",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nature.com/nature/articles?type=research-highlight",
      "title": "Research Highlights | Nature",
      "type": "feed",
      "url": "rsshub://nature/highlight/nature"
    },
    {
      "description": "Browse the archive of articles on Nature - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73724428627161091",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nature.com/nature/articles?type=research-highlight",
      "title": "Research Highlights | Nature",
      "type": "feed",
      "url": "rsshub://nature/highlight"
    }
  ]
}
```
