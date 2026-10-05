# GitHub - User Event

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/user_event/:username/:types?`
- Route Name: `User Event`
- Example: `/github/user_event/mslxl`
- URL: `github.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `mslxl`
- Source Location: `user-event.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: Username
- `types`: {"default": "all", "description": "Event types to include, comma separated", "options": [{"label": "All events", "value": "all"}, {"label": "Create events", "value": "create"}, {"label": "Delete events", "value": "delete"}, {"label": "Fork events", "value": "fork"}, {"label": "Issue create events", "value": "issue"}, {"label": "Issue comment events", "value": "issuecomm"}, {"label": "Member events", "value": "member"}, {"label": "Pull request events", "value": "pr"}, {"label": "Pull request review comment events", "value": "prcomm"}, {"label": "Pull request review events", "value": "prrev"}, {"label": "Public events", "value": "public"}, {"label": "Push events", "value": "push"}, {"label": "Release events", "value": "release"}, {"label": "Watch events (stars)", "value": "star"}, {"label": "Wiki item create or update events", "value": "wiki"}, {"label": "Commit comment events", "value": "cmcomm"}, {"label": "Discussion events", "value": "discussion"}]}


## Features
- `requireConfig`: [{"description": "GitHub access token to access private repository events", "name": "GITHUB_ACCESS_TOKEN", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `github.com/:username`
- `target`: `/user_event/:username`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/user_event/mslxl",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "GitHub access token to access private repository events",
        "name": "GITHUB_ACCESS_TOKEN",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "user-event.ts",
  "maintainers": [
    "mslxl"
  ],
  "name": "User Event",
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
          "label": "Issue create events",
          "value": "issue"
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
          "label": "Pull request review events",
          "value": "prrev"
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
        },
        {
          "label": "Wiki item create or update events",
          "value": "wiki"
        },
        {
          "label": "Commit comment events",
          "value": "cmcomm"
        },
        {
          "label": "Discussion events",
          "value": "discussion"
        }
      ]
    },
    "username": "Username"
  },
  "path": "/user_event/:username/:types?",
  "radar": [
    {
      "source": [
        "github.com/:username"
      ],
      "target": "/user_event/:username"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "GitHub events received by azmiao - includes private events - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "206906436885556224",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/azmiao",
      "title": "azmiao GitHub User Feed - All Events",
      "type": "feed",
      "url": "rsshub://github/user_event/azmiao"
    }
  ],
  "view": 5
}
```
