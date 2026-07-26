# JavTrailers - Studios

## Coverage
`index-only`

## Route
- Namespace: `javtrailers`
- Namespace Name: `JavTrailers`
- Route Path: `/javtrailers/studios/:studio`
- Route Name: `Studios`
- Example: `/javtrailers/studios/s1-no-1-style`
- URL: `javtrailers.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `studios.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `studio`: Studio name, can be found in the URL of the studio page


## Features
- `nsfw`: true
- `requirePuppeteer`: true

## Radar
### Rule 1
- `source`:
  - `javtrailers.com/studios/:category`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/javtrailers/studios/s1-no-1-style",
  "features": {
    "nsfw": true,
    "requirePuppeteer": true
  },
  "heat": 31,
  "location": "studios.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Studios",
  "parameters": {
    "studio": "Studio name, can be found in the URL of the studio page"
  },
  "path": "/studios/:studio",
  "radar": [
    {
      "source": [
        "javtrailers.com/studios/:category"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Watch Jav made by Prestige free, with high definition, we have over 4,000 studios available for free streaming. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "80227253777350656",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javtrailers.com/studios/s1-no-1-style",
      "title": "SSNI OFJE Jav Online | Japanese Adult Video - JavTrailers.com",
      "type": "feed",
      "url": "rsshub://javtrailers/studios/s1-no-1-style"
    },
    {
      "description": "Watch Jav made by Prestige free, with high definition, we have over 4,000 studios available for free streaming. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "176520262640196608",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javtrailers.com/studios/dogma",
      "title": "Dogma Jav Online | Japanese Adult Video - JavTrailers.com",
      "type": "feed",
      "url": "rsshub://javtrailers/studios/dogma"
    }
  ]
}
```
