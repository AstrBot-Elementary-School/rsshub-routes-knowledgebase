# MDPI - Journal

## Coverage
`index-only`

## Route
- Namespace: `mdpi`
- Namespace Name: `MDPI`
- Route Path: `/mdpi/:journal`
- Route Name: `Journal`
- Example: `/mdpi/analytica`
- URL: `www.mdpi.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `Derekmini`
- Source Location: `journal.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `journal`: Journal Name, get it from the journal homepage


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
  - `www.mdpi.com/journal/:journal`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/mdpi/analytica",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 12,
  "location": "journal.tsx",
  "maintainers": [
    "Derekmini"
  ],
  "name": "Journal",
  "parameters": {
    "journal": "Journal Name, get it from the journal homepage"
  },
  "path": "/:journal",
  "radar": [
    {
      "source": [
        "www.mdpi.com/journal/:journal"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Remote Sensing - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "85233533576043520",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mdpi.com/journal/remotesensing",
      "title": "Remote Sensing",
      "type": "feed",
      "url": "rsshub://mdpi/remotesensing"
    },
    {
      "description": "Nutrients - Powered by RSSHub",
      "errorAt": "2025-08-18T10:52:10.569Z",
      "errorMessage": "[GET] \"https://www.mdpi.com/journal/nutrients\": 403 Forbidden\n",
      "id": "85211433371259904",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mdpi.com/journal/nutrients",
      "title": "Nutrients",
      "type": "feed",
      "url": "rsshub://mdpi/nutrients"
    }
  ]
}
```
