# The University of Chicago Press: Journals - Current Issue

## Coverage
`index-only`

## Route
- Namespace: `uchicago`
- Namespace Name: `The University of Chicago Press: Journals`
- Route Path: `/uchicago/journals/current/:journal`
- Route Name: `Current Issue`
- Example: `/uchicago/journals/current/jpe`
- URL: `journals.uchicago.edu`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `TonyRL`
- Source Location: `current.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `journal`: Journal id, can be found in URL. [Browse journals by title](https://www.journals.uchicago.edu/action/showPublications)


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `journals.uchicago.edu/toc/:journal/current`
  - `journals.uchicago.edu/journal/:journal`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/uchicago/journals/current/jpe",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "current.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Current Issue",
  "parameters": {
    "journal": "Journal id, can be found in URL. [Browse journals by title](https://www.journals.uchicago.edu/action/showPublications)"
  },
  "path": "/journals/current/:journal",
  "radar": [
    {
      "source": [
        "journals.uchicago.edu/toc/:journal/current",
        "journals.uchicago.edu/journal/:journal"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Lead Editor: Esteban Rossi-Hansberg Editors: John Asker, Andrew Atkeson, Leonardo Bursztyn, Gabriel Carroll, Melissa Dell, David Lagakos, Guido Lorenzoni, Francesca Molinari, Luigi Pistaferri, Bruno Strulovici, Christopher Taber, Christopher Walters - Powered by RSSHub",
      "errorAt": "2026-07-07T09:18:43.490Z",
      "errorMessage": "browserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "74375516441159680",
      "image": "https://www.journals.uchicago.edu/cms/asset/cbf24731-85ef-41cf-8559-e373014c64bf/jpe.2026.134.issue-7.cover.png",
      "ownerUserId": null,
      "siteUrl": "https://www.journals.uchicago.edu/toc/jpe/current",
      "title": "Journal of Political Economy | Vol 134, No 7",
      "type": "feed",
      "url": "rsshub://uchicago/journals/current/jpe"
    },
    {
      "description": "Editors: Mary Evans, Teevrat Garg, Arik Levinson, and Andrew Plantinga Published for the Association of Environmental and Resource Economists - Powered by RSSHub",
      "errorAt": "2026-07-07T09:47:14.897Z",
      "errorMessage": "browserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "75184870917658624",
      "image": "https://www.journals.uchicago.edu/cms/asset/5a38d4f1-b01f-4f38-830f-3718a574ab3d/default_cover.gif",
      "ownerUserId": null,
      "siteUrl": "https://www.journals.uchicago.edu/toc/jaere/current",
      "title": "Journal of the Association of Environmental and Resource Economists | Vol 13, No 5",
      "type": "feed",
      "url": "rsshub://uchicago/journals/current/jaere"
    }
  ]
}
```
