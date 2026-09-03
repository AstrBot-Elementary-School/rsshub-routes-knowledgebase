# Android - Security Bulletins

## Coverage
`index-only`

## Route
- Namespace: `android`
- Namespace Name: `Android`
- Route Path: `/android/security-bulletin`
- Route Name: `Security Bulletins`
- Example: `/android/security-bulletin`
- URL: `source.android.com/docs/security/bulletin/asb-overview`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `TonyRL`
- Source Location: `security-bulletin.ts`
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

## Radar
### Rule 1
- `source`:
  - `source.android.com/docs/security/bulletin`
  - `source.android.com/docs/security/bulletin/asb-overview`
  - `source.android.com/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/android/security-bulletin",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "security-bulletin.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Security Bulletins",
  "parameters": {},
  "path": "/security-bulletin",
  "radar": [
    {
      "source": [
        "source.android.com/docs/security/bulletin",
        "source.android.com/docs/security/bulletin/asb-overview",
        "source.android.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 312599500429 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Android Security Bulletins | Android Open Source Project - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "156000891791099904",
      "image": "https://www.gstatic.com/devrel-devsite/prod/v6c08f9bb601564cd99488472d05cdf6fb06f007f31b6552465782b15883ce123/androidsource/images/touchicon-180.png",
      "ownerUserId": null,
      "siteUrl": "https://source.android.com/docs/security/bulletin/asb-overview",
      "title": "Android Security Bulletins | Android Open Source Project",
      "type": "feed",
      "url": "rsshub://android/security-bulletin"
    }
  ],
  "url": "source.android.com/docs/security/bulletin/asb-overview"
}
```
