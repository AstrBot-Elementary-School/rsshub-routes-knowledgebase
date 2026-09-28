# Greasy Fork - Script Feedback

## Coverage
`index-only`

## Route
- Namespace: `greasyfork`
- Namespace Name: `Greasy Fork`
- Route Path: `/greasyfork/scripts/:script/feedback`
- Route Name: `Script Feedback`
- Example: `/greasyfork/scripts/431691-bypass-all-shortlinks/feedback`
- URL: `greasyfork.org`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `miles170`
- Source Location: `feedback.ts`
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
  - `greasyfork.org/:language/scripts/:script/feedback`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/greasyfork/scripts/431691-bypass-all-shortlinks/feedback",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "feedback.ts",
  "maintainers": [
    "miles170"
  ],
  "name": "Script Feedback",
  "parameters": {
    "script": "Script id, can be found in URL"
  },
  "path": "/scripts/:script/feedback",
  "radar": [
    {
      "source": [
        "greasyfork.org/:language/scripts/:script/feedback"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Bypass All Shortlinks - Feedback - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "126248142565489664",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://greasyfork.org/scripts/431691-bypass-all-shortlinks/feedback",
      "title": "Bypass All Shortlinks - Feedback",
      "type": "feed",
      "url": "rsshub://greasyfork/scripts/431691-bypass-all-shortlinks/feedback"
    }
  ]
}
```
