# Infuse - Release Notes

## Coverage
`index-only`

## Route
- Namespace: `firecore`
- Namespace Name: `Infuse`
- Route Path: `/firecore/:os`
- Route Name: `Release Notes`
- Example: `/firecore/ios`
- URL: `firecore.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `NathanDai`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `os`: `ios`,`tvos`,`macos`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/firecore/ios",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 15,
  "location": "index.ts",
  "maintainers": [
    "NathanDai"
  ],
  "name": "Release Notes",
  "parameters": {
    "os": "`ios`,`tvos`,`macos`"
  },
  "path": "/:os",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Infuse Release Notes (ios) - Powered by RSSHub",
      "errorAt": "2026-04-19T03:14:57.188Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "55457641912958985",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://firecore.com/releases",
      "title": "Infuse Release Notes (ios)",
      "type": "feed",
      "url": "rsshub://firecore/ios"
    },
    {
      "description": "Infuse Release Notes (macos) - Powered by RSSHub",
      "errorAt": "2026-04-19T07:28:18.487Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "66384086512693248",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://firecore.com/releases",
      "title": "Infuse Release Notes (macos)",
      "type": "feed",
      "url": "rsshub://firecore/macos"
    }
  ]
}
```
