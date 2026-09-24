# F95zone - Post

## Coverage
`index-only`

## Route
- Namespace: `f95zone`
- Namespace Name: `F95zone`
- Route Path: `/f95zone/post/:thread/:postId`
- Route Name: `Post`
- Example: `/f95zone/post/vicineko-collection-2025-06-14-vicineko.84596/post-5909830`
- URL: `f95zone.to`
- Language: `_None_`
- Categories: `game`
- Maintainers: `wsmbsbbz`
- Source Location: `post.ts`
- Source Module: `_None_`

## Description
Track content changes of a specific post. Uses the date `[yyyy-mm-dd]` in title for update detection.

URL format: `https://f95zone.to/threads/{thread}/#post-{id}` → replace `#` with `/` to get `/f95zone/post/{thread}/post-{id}`

Example: `https://f95zone.to/threads/vicineko-collection-2025-06-14-vicineko.84596/#post-5909830` → `/f95zone/post/vicineko-collection-2025-06-14-vicineko.84596/post-5909830`

Note: This route does not support Radar auto-detection because the post ID is in the URL hash (after `#`), which cannot be extracted by Radar. You need to manually construct the subscription URL.

## Parameters
- `thread`: Thread slug with ID
- `postId`: Post ID with `post-` prefix, replace `#` with `/` from browser URL


## Features
- `requireConfig`: [{"description": "F95zone cookie for accessing restricted content.", "name": "F95ZONE_COOKIE", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "Track content changes of a specific post. Uses the date `[yyyy-mm-dd]` in title for update detection.\n\nURL format: `https://f95zone.to/threads/{thread}/#post-{id}` → replace `#` with `/` to get `/f95zone/post/{thread}/post-{id}`\n\nExample: `https://f95zone.to/threads/vicineko-collection-2025-06-14-vicineko.84596/#post-5909830` → `/f95zone/post/vicineko-collection-2025-06-14-vicineko.84596/post-5909830`\n\nNote: This route does not support Radar auto-detection because the post ID is in the URL hash (after `#`), which cannot be extracted by Radar. You need to manually construct the subscription URL.",
  "example": "/f95zone/post/vicineko-collection-2025-06-14-vicineko.84596/post-5909830",
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
  "heat": 11,
  "location": "post.ts",
  "maintainers": [
    "wsmbsbbz"
  ],
  "name": "Post",
  "parameters": {
    "postId": "Post ID with `post-` prefix, replace `#` with `/` from browser URL",
    "thread": "Thread slug with ID"
  },
  "path": "/post/:thread/:postId",
  "radar": [],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "[F95zone] Collection Video Ubermation Collection [2026-05-16] [Uebermation/Übermation] - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "242891845605645312",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://f95zone.to/threads/ubermation-collection-2026-01-19-uebermation-uebermation.231247/#post-15251821",
      "title": "[F95zone] Collection Video Ubermation Collection [2026-05-16] [Uebermation/Übermation]",
      "type": "feed",
      "url": "rsshub://f95zone/post/ubermation-collection-2026-01-19-uebermation-uebermation.231247/post-15251821"
    },
    {
      "description": "[F95zone] Collection Video Lazy Procrastinator Collection [2026-06-28] [LazyProcrastinator/LazyProcrast] - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "250523611655439360",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://f95zone.to/threads/lazy-procrastinator-collection-2025-04-18-lazyprocrastinator-lazyprocrast.50685/#post-3358507",
      "title": "[F95zone] Collection Video Lazy Procrastinator Collection [2026-06-28] [LazyProcrastinator/LazyProcrast]",
      "type": "feed",
      "url": "rsshub://f95zone/post/lazy-procrastinator-collection-2025-04-18-lazyprocrastinator-lazyprocrast.50685/post-3358507"
    }
  ]
}
```
