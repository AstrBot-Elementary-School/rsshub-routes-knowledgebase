# LineageOS - Changes

## Coverage
`index-only`

## Route
- Namespace: `lineageos`
- Namespace Name: `LineageOS`
- Route Path: `/lineageos/changes`
- Route Name: `Changes`
- Example: `/lineageos/changes`
- URL: `download.lineageos.org`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `changes.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `download.lineageos.org/changes`
- `target`: `/changes`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/lineageos/changes",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 8,
  "location": "changes.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Changes",
  "path": "/changes",
  "radar": [
    {
      "source": [
        "download.lineageos.org/changes"
      ],
      "target": "/changes"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "LineageOS Downloads - Downloads - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "165677992919531520",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://download.lineageos.org/changes",
      "title": "LineageOS Downloads - Downloads",
      "type": "feed",
      "url": "rsshub://lineageos/changes"
    }
  ],
  "url": "download.lineageos.org",
  "view": 5
}
```
