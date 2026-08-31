# Unraid - Community Apps

## Coverage
`index-only`

## Route
- Namespace: `unraid`
- Namespace Name: `Unraid`
- Route Path: `/unraid/community-apps`
- Route Name: `Community Apps`
- Example: `/unraid/community-apps`
- URL: `unraid.net/community/apps`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `KTachibanaM`
- Source Location: `community-apps.ts`
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
  - `unraid.net/community/apps`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/unraid/community-apps",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "community-apps.ts",
  "maintainers": [
    "KTachibanaM"
  ],
  "name": "Community Apps",
  "parameters": {},
  "path": "/community-apps",
  "radar": [
    {
      "source": [
        "unraid.net/community/apps"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(13) ] to not include 'https://github.com/orgs/CasaVargas/pa…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Unraid Community Apps - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61229729954450432",
      "image": "https://craftassets.unraid.net/static/favicon/favicon.ico?v=1.0",
      "ownerUserId": null,
      "siteUrl": "https://unraid.net/community/apps",
      "title": "Unraid Community Apps",
      "type": "feed",
      "url": "rsshub://unraid/community-apps"
    }
  ],
  "url": "unraid.net/community/apps"
}
```
