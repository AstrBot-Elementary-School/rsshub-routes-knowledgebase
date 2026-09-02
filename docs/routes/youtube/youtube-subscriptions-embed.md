# YouTube - Subscriptions

## Coverage
`index-only`

## Route
- Namespace: `youtube`
- Namespace Name: `YouTube`
- Route Path: `/youtube/subscriptions/:embed?`
- Route Name: `Subscriptions`
- Example: `/youtube/subscriptions`
- URL: `www.youtube.com/feed/subscriptions`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `subscriptions.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `embed`: Default to embed the video, set to any value to disable embedding


## Features
- `requireConfig`: [{"description": "", "name": "YOUTUBE_KEY"}, {"description": "", "name": "YOUTUBE_CLIENT_ID"}, {"description": "", "name": "YOUTUBE_CLIENT_SECRET"}, {"description": "", "name": "YOUTUBE_REFRESH_TOKEN"}]

## Radar
### Rule 1
- `source`:
  - `www.youtube.com/feed/subscriptions`
  - `www.youtube.com/feed/channels`
- `target`: `/subscriptions`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/youtube/subscriptions",
  "features": {
    "requireConfig": [
      {
        "description": "",
        "name": "YOUTUBE_KEY"
      },
      {
        "description": "",
        "name": "YOUTUBE_CLIENT_ID"
      },
      {
        "description": "",
        "name": "YOUTUBE_CLIENT_SECRET"
      },
      {
        "description": "",
        "name": "YOUTUBE_REFRESH_TOKEN"
      }
    ]
  },
  "heat": 24,
  "location": "subscriptions.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Subscriptions",
  "parameters": {
    "embed": "Default to embed the video, set to any value to disable embedding"
  },
  "path": "/subscriptions/:embed?",
  "radar": [
    {
      "source": [
        "www.youtube.com/feed/subscriptions",
        "www.youtube.com/feed/channels"
      ],
      "target": "/subscriptions"
    }
  ],
  "topFeeds": [
    {
      "description": "YouTube Subscriptions - Powered by RSSHub",
      "errorAt": "2025-03-08T16:50:14.180Z",
      "errorMessage": "YouTube RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#route-specific-configurations\">relevant config</a>\n",
      "id": "121166426445163520",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "rsshub://youtube/www.youtube.com/feed/subscriptions",
      "title": "Subscriptions - YouTube",
      "type": "feed",
      "url": "rsshub://youtube/subscriptions"
    }
  ],
  "url": "www.youtube.com/feed/subscriptions"
}
```
