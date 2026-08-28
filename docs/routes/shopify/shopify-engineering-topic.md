# Shopify - Engineering

## Coverage
`index-only`

## Route
- Namespace: `shopify`
- Namespace Name: `Shopify`
- Route Path: `/shopify/engineering/:topic?`
- Route Name: `Engineering`
- Example: `/shopify/engineering`
- URL: `shopify.engineering/latest`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `zhsama`
- Source Location: `engineering.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: Topic slug from `/topics/:topic`, e.g. `mobile`, `ai-machine-learning`. Defaults to the latest listing.


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
  - `shopify.engineering/`
  - `shopify.engineering/latest`
- `target`: `/engineering`
### Rule 2
- `source`:
  - `shopify.engineering/topics/:topic`
- `target`: `/engineering/:topic`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/shopify/engineering",
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
  "location": "engineering.ts",
  "maintainers": [
    "zhsama"
  ],
  "name": "Engineering",
  "parameters": {
    "topic": "Topic slug from `/topics/:topic`, e.g. `mobile`, `ai-machine-learning`. Defaults to the latest listing."
  },
  "path": "/engineering/:topic?",
  "radar": [
    {
      "source": [
        "shopify.engineering/",
        "shopify.engineering/latest"
      ],
      "target": "/engineering"
    },
    {
      "source": [
        "shopify.engineering/topics/:topic"
      ],
      "target": "/engineering/:topic"
    }
  ],
  "topFeeds": [],
  "url": "shopify.engineering/latest"
}
```
