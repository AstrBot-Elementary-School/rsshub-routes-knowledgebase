# LinkedIn - Company Posts

## Coverage
`index-only`

## Route
- Namespace: `linkedin`
- Namespace Name: `LinkedIn`
- Route Path: `/linkedin/company/:company_id/posts`
- Route Name: `Company Posts`
- Example: `/linkedin/company/google/posts`
- URL: `linkedin.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `saifazmi`
- Source Location: `posts.ts`
- Source Module: `_None_`

## Description
Get company's LinkedIn posts by company ID

## Parameters
- `company_id`: Company's LinkedIn profile ID


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportRadar`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "Get company's LinkedIn posts by company ID",
  "example": "/linkedin/company/google/posts",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": false,
    "supportScihub": false
  },
  "heat": 36,
  "location": "posts.ts",
  "maintainers": [
    "saifazmi"
  ],
  "name": "Company Posts",
  "parameters": {
    "company_id": "Company's LinkedIn profile ID"
  },
  "path": "/company/:company_id/posts",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "This feed gets GreatFrontEnd's posts from LinkedIn - Powered by RSSHub",
      "errorAt": "2026-08-22T17:21:07.784Z",
      "errorMessage": "browserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.61                          ║\n║   - client version: v1.62                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "173633672770214912",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.linkedin.com/company/greatfrontend",
      "title": "LinkedIn - GreatFrontEnd's Posts",
      "type": "feed",
      "url": "rsshub://linkedin/company/greatfrontend/posts"
    },
    {
      "description": "This feed gets CellMark's posts from LinkedIn - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "155076041493307392",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.linkedin.com/company/cellmark",
      "title": "LinkedIn - CellMark's Posts",
      "type": "feed",
      "url": "rsshub://linkedin/company/cellmark/posts"
    }
  ]
}
```
