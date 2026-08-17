# Neat Download Manager - Download

## Coverage
`index-only`

## Route
- Namespace: `neatdownloadmanager`
- Namespace Name: `Neat Download Manager`
- Route Path: `/neatdownloadmanager/download/:os?`
- Route Name: `Download`
- Example: `/neatdownloadmanager/download`
- URL: `neatdownloadmanager.com/index.php`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `download.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `os`: Operating system, windows or macos, all by default


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
  - `neatdownloadmanager.com/index.php`
  - `neatdownloadmanager.com/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/neatdownloadmanager/download",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10,
  "location": "download.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Download",
  "parameters": {
    "os": "Operating system, windows or macos, all by default"
  },
  "path": "/download/:os?",
  "radar": [
    {
      "source": [
        "neatdownloadmanager.com/index.php",
        "neatdownloadmanager.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Neat Download Manager - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "79871530629426176",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.neatdownloadmanager.com/index.php",
      "title": "Neat Download Manager",
      "type": "feed",
      "url": "rsshub://neatdownloadmanager/download"
    },
    {
      "description": "Neat Download Manager - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "198683230830132224",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.neatdownloadmanager.com/index.php",
      "title": "Neat Download Manager",
      "type": "feed",
      "url": "rsshub://neatdownloadmanager/download/windows"
    }
  ],
  "url": "neatdownloadmanager.com/index.php"
}
```
