# Greasy Fork - Script Version History

## Coverage
`index-only`

## Route
- Namespace: `greasyfork`
- Namespace Name: `Greasy Fork`
- Route Path: `/greasyfork/scripts/:script/versions`
- Route Name: `Script Version History`
- Example: `/greasyfork/scripts/431691-bypass-all-shortlinks/versions`
- URL: `greasyfork.org`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `miles170`
- Source Location: `versions.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `script`: Script id, can be found in URL


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
  - `greasyfork.org/:language/scripts/:script/versions`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/greasyfork/scripts/431691-bypass-all-shortlinks/versions",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "versions.ts",
  "maintainers": [
    "miles170"
  ],
  "name": "Script Version History",
  "parameters": {
    "script": "Script id, can be found in URL"
  },
  "path": "/scripts/:script/versions",
  "radar": [
    {
      "source": [
        "greasyfork.org/:language/scripts/:script/versions"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Bypass All Shortlinks - Version history - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "126248310850640896",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://greasyfork.org/scripts/431691-bypass-all-shortlinks/versions",
      "title": "Bypass All Shortlinks - Version history",
      "type": "feed",
      "url": "rsshub://greasyfork/scripts/431691-bypass-all-shortlinks/versions"
    }
  ]
}
```
