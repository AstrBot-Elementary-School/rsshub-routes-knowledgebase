# SupChina - Podcasts

## Coverage
`index-only`

## Route
- Namespace: `supchina`
- Namespace Name: `SupChina`
- Route Path: `/supchina/podcasts`
- Route Name: `Podcasts`
- Example: `/supchina/podcasts`
- URL: `thechinaproject.com/podcasts`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `podcasts.ts`
- Source Module: `_None_`

## Description
The China Project, formerly SupChina, closed in November 2023. This route provides its official podcast archive. Some archived episodes are no longer available from the audio host.

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `supchina.com/podcasts`
  - `supchina.com/`
### Rule 2
- `source`:
  - `thechinaproject.com/podcasts`
  - `thechinaproject.com/`
- `target`: `/podcasts`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "The China Project, formerly SupChina, closed in November 2023. This route provides its official podcast archive. Some archived episodes are no longer available from the audio host.",
  "example": "/supchina/podcasts",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "podcasts.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Podcasts",
  "parameters": {},
  "path": "/podcasts",
  "radar": [
    {
      "source": [
        "supchina.com/podcasts",
        "supchina.com/"
      ]
    },
    {
      "source": [
        "thechinaproject.com/podcasts",
        "thechinaproject.com/"
      ],
      "target": "/podcasts"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "thechinaproject.com/podcasts"
}
```
