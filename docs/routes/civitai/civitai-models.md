# Civitai - Latest models

## Coverage
`index-only`

## Route
- Namespace: `civitai`
- Namespace Name: `Civitai`
- Route Path: `/civitai/models`
- Route Name: `Latest models`
- Example: `/civitai/models`
- URL: `civitai.com/`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `DIYgod`
- Source Location: `models.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `civitai.com/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/civitai/models",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 59,
  "location": "models.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Latest models",
  "parameters": {},
  "path": "/models",
  "radar": [
    {
      "source": [
        "civitai.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Civitai latest models - Powered by RSSHub",
      "errorAt": "2026-09-03T05:32:17.958Z",
      "errorMessage": "Failed query: select \"id\", \"guid\", \"media\" from \"entries\" \"entries\" where \"entries\".\"feed_id\" = $1\nparams: 57092092744427520",
      "id": "57092092744427520",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://civitai.com/",
      "title": "Civitai latest models",
      "type": "feed",
      "url": "rsshub://civitai/models"
    }
  ],
  "url": "civitai.com/"
}
```
