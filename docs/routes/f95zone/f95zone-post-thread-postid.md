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
      "description": "[F95zone] Collection Video Nyl Collection [2026-01-31] [Nyl2] - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "250524266322800640",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://f95zone.to/threads/nyl-collection-2026-01-01-nyl2.46099/#post-3049831",
      "title": "[F95zone] Collection Video Nyl Collection [2026-01-31] [Nyl2]",
      "type": "feed",
      "url": "rsshub://f95zone/post/nyl-collection-2026-01-01-nyl2.46099/post-3049831"
    },
    {
      "description": "[F95zone] Collection Video Wildeer Studio Collection [2026-01-13] [WildeerStudio] - Powered by RSSHub",
      "errorAt": "2026-07-07T21:43:05.931Z",
      "errorMessage": "[GET] \"https://f95zone.to/threads/wildeer-studio-collection-2026-01-13-wildeerstudio.44606/#post-2953877\": 451 Unavailable For Legal Reasons\n",
      "id": "250523893545644032",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://f95zone.to/threads/wildeer-studio-collection-2026-01-13-wildeerstudio.44606/#post-2953877",
      "title": "[F95zone] Collection Video Wildeer Studio Collection [2026-01-13] [WildeerStudio]",
      "type": "feed",
      "url": "rsshub://f95zone/post/wildeer-studio-collection-2026-01-13-wildeerstudio.44606/post-2953877"
    }
  ]
}
```
