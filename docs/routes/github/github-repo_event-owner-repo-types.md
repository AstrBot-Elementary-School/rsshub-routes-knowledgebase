# GitHub - Repository Event

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/repo_event/:owner/:repo/:types?`
- Route Name: `Repository Event`
- Example: `/github/repo_event/DIYgod/RSSHub`
- URL: `github.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `mslxl`
- Source Location: `repo-event.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `owner`: Username or organization name
- `repo`: Repository name
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
  - `github.com/:owner/:repo`
- `target`: `/repo_event/:owner/:repo`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/repo_event/DIYgod/RSSHub",
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
  "heat": 0,
  "location": "repo-event.ts",
  "maintainers": [
    "mslxl"
  ],
  "name": "Repository Event",
  "parameters": {
    "owner": "Username or organization name",
    "repo": "Repository name",
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
    }
  },
  "path": "/repo_event/:owner/:repo/:types?",
  "radar": [
    {
      "source": [
        "github.com/:owner/:repo"
      ],
      "target": "/repo_event/:owner/:repo"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "view": 5
}
```
