# Mozilla - New Release

## Coverage
`index-only`

## Route
- Namespace: `firefox`
- Namespace Name: `Mozilla`
- Route Path: `/firefox/release/:platform?`
- Route Name: `New Release`
- Example: `/firefox/release/desktop`
- URL: `monitor.firefox.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `fengkx`
- Source Location: `release.ts`
- Source Module: `_None_`

## Description
| Desktop | Android | Beta | Nightly | iOS |
| ------- | ------- | ---- | ------- | --- |
| desktop | android | beta | nightly | ios |

## Parameters
- `platform`: the platform


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "| Desktop | Android | Beta | Nightly | iOS |\n| ------- | ------- | ---- | ------- | --- |\n| desktop | android | beta | nightly | ios |",
  "example": "/firefox/release/desktop",
  "heat": 3,
  "location": "release.ts",
  "maintainers": [
    "fengkx"
  ],
  "name": "New Release",
  "parameters": {
    "platform": "the platform"
  },
  "path": "/release/:platform?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Firefox nightly release notes - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55873602868576273",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mozilla.org/en-US/firefox/nightly/notes",
      "title": "Firefox nightly release notes",
      "type": "feed",
      "url": "rsshub://firefox/release/nightly"
    },
    {
      "description": "Firefox beta release notes - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72287537564742660",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mozilla.org/en-US/firefox/beta/notes",
      "title": "Firefox beta release notes",
      "type": "feed",
      "url": "rsshub://firefox/release/beta"
    }
  ]
}
```
