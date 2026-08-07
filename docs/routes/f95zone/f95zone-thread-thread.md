# F95zone - Thread

## Coverage
`index-only`

## Route
- Namespace: `f95zone`
- Namespace Name: `F95zone`
- Route Path: `/f95zone/thread/:thread`
- Route Name: `Thread`
- Example: `/f95zone/thread/ubermation-collection-2026-01-19-uebermation-uebermation.231247`
- URL: `f95zone.to`
- Language: `_None_`
- Categories: `game`
- Maintainers: `wsmbsbbz`
- Source Location: `thread.ts`
- Source Module: `_None_`

## Description
Track replies in a thread. Fetches the first page and the last page.

URL format: `https://f95zone.to/threads/{thread}/` → use `{thread}` as the parameter.

Example: `https://f95zone.to/threads/ubermation-collection-2026-01-19-uebermation-uebermation.231247/` → `/f95zone/thread/ubermation-collection-2026-01-19-uebermation-uebermation.231247`

Note: If you want to track a specific post's content changes (e.g., first post with download links), use the `/f95zone/post` route instead.

## Parameters
- `thread`: Thread slug with ID, copy from browser URL after `/threads/`


## Features
- `requireConfig`: [{"description": "F95zone cookie for accessing restricted content.", "name": "F95ZONE_COOKIE", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `f95zone.to/threads/:thread/*`
- `target`: `/thread/:thread`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "Track replies in a thread. Fetches the first page and the last page.\n\nURL format: `https://f95zone.to/threads/{thread}/` → use `{thread}` as the parameter.\n\nExample: `https://f95zone.to/threads/ubermation-collection-2026-01-19-uebermation-uebermation.231247/` → `/f95zone/thread/ubermation-collection-2026-01-19-uebermation-uebermation.231247`\n\nNote: If you want to track a specific post's content changes (e.g., first post with download links), use the `/f95zone/post` route instead.",
  "example": "/f95zone/thread/ubermation-collection-2026-01-19-uebermation-uebermation.231247",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "F95zone cookie for accessing restricted content.",
        "name": "F95ZONE_COOKIE",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "thread.ts",
  "maintainers": [
    "wsmbsbbz"
  ],
  "name": "Thread",
  "parameters": {
    "thread": "Thread slug with ID, copy from browser URL after `/threads/`"
  },
  "path": "/thread/:thread",
  "radar": [
    {
      "source": [
        "f95zone.to/threads/:thread/*"
      ],
      "target": "/thread/:thread"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "[F95zone] Collection GIF Video theobrobine Collection [2026-06-24] [THEOBROBINE/theobrobine/ておぶろびん] - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "250446303116526592",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://f95zone.to/threads/theobrobine-collection-2025-12-28-theobrobine-theobrobine-teoburobin.93491/",
      "title": "[F95zone] Collection GIF Video theobrobine Collection [2026-06-24] [THEOBROBINE/theobrobine/ておぶろびん]",
      "type": "feed",
      "url": "rsshub://f95zone/thread/theobrobine-collection-2025-12-28-theobrobine-theobrobine-teoburobin.93491"
    },
    {
      "description": "[F95zone] Collection Video Ubermation Collection [2026-05-16] [Uebermation/Übermation] - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "250445877936302080",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://f95zone.to/threads/ubermation-collection-2025-10-06-uebermation-uebermation.231247/",
      "title": "[F95zone] Collection Video Ubermation Collection [2026-05-16] [Uebermation/Übermation]",
      "type": "feed",
      "url": "rsshub://f95zone/thread/ubermation-collection-2025-10-06-uebermation-uebermation.231247"
    }
  ]
}
```
