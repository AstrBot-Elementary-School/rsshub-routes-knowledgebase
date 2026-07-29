# ACS Publications - Journal

## Coverage
`index-only`

## Route
- Namespace: `acs`
- Namespace Name: `ACS Publications`
- Route Path: `/acs/journal/:id`
- Route Name: `Journal`
- Example: `/acs/journal/jacsat`
- URL: `pubs.acs.org`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `journal.tsx`
- Source Module: `_None_`

## Description
::: tip
See [Browse Content](https://pubs.acs.org)
:::

## Parameters
- `id`: Journal id, can be found in URL


## Features
- `supportScihub`: true

## Radar
### Rule 1
- `source`:
  - `pubs.acs.org/journal/:id`
  - `pubs.acs.org/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "::: tip\nSee [Browse Content](https://pubs.acs.org)\n:::",
  "example": "/acs/journal/jacsat",
  "features": {
    "supportScihub": true
  },
  "heat": 7,
  "location": "journal.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Journal",
  "parameters": {
    "id": "Journal id, can be found in URL"
  },
  "path": "/journal/:id",
  "radar": [
    {
      "source": [
        "pubs.acs.org/journal/:id",
        "pubs.acs.org/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "Environmental Science & Technology - Powered by RSSHub",
      "errorAt": "2025-05-15T04:38:45.143Z",
      "errorMessage": "Waiting for selector `.toc` failed: waitForFunction failed: frame got detached.\nbrowserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.59                          ║\n║   - client version: v1.60                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.59                          ║\n║   - client version: v1.60                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "84129903603684352",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://pubs.acs.org/toc/esthag/0/0",
      "title": "Environmental Science & Technology",
      "type": "feed",
      "url": "rsshub://acs/journal/esthag"
    },
    {
      "description": "Journal of Chemical Theory and Computation - Powered by RSSHub",
      "errorAt": "2026-07-25T15:56:09.934Z",
      "errorMessage": "page.waitForSelector: Target page, context or browser has been closed\n",
      "id": "1161502729202171904",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://pubs.acs.org/toc/jctcce/0/0",
      "title": "Journal of Chemical Theory and Computation",
      "type": "feed",
      "url": "rsshub://acs/journal/jctcce"
    }
  ]
}
```
