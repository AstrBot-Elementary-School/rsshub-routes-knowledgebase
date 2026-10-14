# Chocolatey - Package

## Coverage
`index-only`

## Route
- Namespace: `chocolatey`
- Namespace Name: `Chocolatey`
- Route Path: `/chocolatey/packages/:id`
- Route Name: `Package`
- Example: `/chocolatey/packages/microsoft-edge`
- URL: `community.chocolatey.org`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `packages.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: {"description": "Package ID"}


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
  - `community.chocolatey.org/packages/:id`
  - `community.chocolatey.org/packages/:id/:version`
- `target`: `/packages/:id`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/chocolatey/packages/microsoft-edge",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 1,
  "location": "packages.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Package",
  "parameters": {
    "id": {
      "description": "Package ID"
    }
  },
  "path": "/packages/:id",
  "radar": [
    {
      "source": [
        "community.chocolatey.org/packages/:id",
        "community.chocolatey.org/packages/:id/:version"
      ],
      "target": "/packages/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Microsoft Edge browser, based on the Chromium open source browser. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "223701545098778624",
      "image": "https://img.chocolatey.org/social-share/facebook-share.png",
      "ownerUserId": null,
      "siteUrl": "https://community.chocolatey.org/packages/microsoft-edge",
      "title": "Chocolatey Software | Microsoft Edge 145.0.3800.97",
      "type": "feed",
      "url": "rsshub://chocolatey/packages/microsoft-edge"
    }
  ],
  "url": "community.chocolatey.org",
  "view": 5,
  "zh": {
    "name": "程序包",
    "parameters": {
      "id": {
        "description": "程序包 ID"
      }
    }
  }
}
```
