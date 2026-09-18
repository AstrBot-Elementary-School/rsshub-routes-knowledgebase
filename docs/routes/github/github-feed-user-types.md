# GitHub - User's Feed

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/feed/:user/:types?`
- Route Name: `User's Feed`
- Example: `/github/feed/yihong0618/star,release,pr`
- URL: `github.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `RtYkk`
- Source Location: `private-feed.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: GitHub username
- `types`: {"default": "all", "description": "Event types to include, comma separated", "options": [{"label": "All events", "value": "all"}, {"label": "Create events", "value": "create"}, {"label": "Delete events", "value": "delete"}, {"label": "Fork events", "value": "fork"}, {"label": "Issue comment events", "value": "issuecomm"}, {"label": "Member events", "value": "member"}, {"label": "Pull request events", "value": "pr"}, {"label": "Pull request review comment events", "value": "prcomm"}, {"label": "Public events", "value": "public"}, {"label": "Push events", "value": "push"}, {"label": "Release events", "value": "release"}, {"label": "Watch events (stars)", "value": "star"}]}


## Features
- `requireConfig`: [{"description": "GitHub access token to access private events", "name": "GITHUB_ACCESS_TOKEN", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `github.com/:user`
- `target`: `/feed/:user`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/feed/yihong0618/star,release,pr",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "GitHub access token to access private events",
        "name": "GITHUB_ACCESS_TOKEN",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "private-feed.ts",
  "maintainers": [
    "RtYkk"
  ],
  "name": "User's Feed",
  "parameters": {
    "types": {
      "default": "all",
      "description": "Event types to include, comma separated",
      "options": [
        {
          "label": "All events",
          "value": "all"
        },
        {
          "label": "Create events",
          "value": "create"
        },
        {
          "label": "Delete events",
          "value": "delete"
        },
        {
          "label": "Fork events",
          "value": "fork"
        },
        {
          "label": "Issue comment events",
          "value": "issuecomm"
        },
        {
          "label": "Member events",
          "value": "member"
        },
        {
          "label": "Pull request events",
          "value": "pr"
        },
        {
          "label": "Pull request review comment events",
          "value": "prcomm"
        },
        {
          "label": "Public events",
          "value": "public"
        },
        {
          "label": "Push events",
          "value": "push"
        },
        {
          "label": "Release events",
          "value": "release"
        },
        {
          "label": "Watch events (stars)",
          "value": "star"
        }
      ]
    },
    "user": "GitHub username"
  },
  "path": "/feed/:user/:types?",
  "radar": [
    {
      "source": [
        "github.com/:user"
      ],
      "target": "/feed/:user"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "GitHub events received by ardubev16 - includes private events - Powered by RSSHub",
      "errorAt": "2025-11-04T02:13:08.676Z",
      "errorMessage": "Failed to fetch\n",
      "id": "182563436143518720",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/ardubev16",
      "title": "ardubev16's GitHub Private Feed - All Events",
      "type": "feed",
      "url": "rsshub://github/feed/ardubev16/all"
    },
    {
      "description": "GitHub events received by free-nodes - includes private events - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "238161917546848256",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/free-nodes",
      "title": "free-nodes's GitHub Private Feed - All Events",
      "type": "feed",
      "url": "rsshub://github/feed/free-nodes/all"
    }
  ],
  "view": 5
}
```
