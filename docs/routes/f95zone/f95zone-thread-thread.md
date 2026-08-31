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
      "description": "[F95zone] Collection Video RDreamer Collection [2025-07-05] [RDreamer] - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "250523197875333120",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://f95zone.to/threads/rdreamer-collection-2025-07-05-rdreamer.253184/",
      "title": "[F95zone] Collection Video RDreamer Collection [2025-07-05] [RDreamer]",
      "type": "feed",
      "url": "rsshub://f95zone/thread/rdreamer-collection-2025-07-05-rdreamer.253184"
    },
    {
      "description": "[F95zone] Collection Video ViciNeko collection [2025-06-14] [ViciNeko] - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "250446095545182208",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://f95zone.to/threads/vicineko-collection-2025-06-14-vicineko.84596/",
      "title": "[F95zone] Collection Video ViciNeko collection [2025-06-14] [ViciNeko]",
      "type": "feed",
      "url": "rsshub://f95zone/thread/vicineko-collection-2025-06-14-vicineko.84596"
    }
  ]
}
```
