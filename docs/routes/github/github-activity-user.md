# GitHub - User Activities

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/activity/:user`
- Route Name: `User Activities`
- Example: `/github/activity/DIYgod`
- URL: `github.com`
- Language: `_None_`
- Categories: `programming, popular`
- Maintainers: `hyoban`
- Source Location: `activity.ts`
- Source Module: `_None_`

## Description
Get the activities of a user on GitHub, based on the GitHub official RSS feed

## Parameters
- `user`: GitHub username


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `github.com/:user`
- `target`: `/activity/:user`

## Raw JSON
```json
{
  "categories": [
    "programming",
    "popular"
  ],
  "description": "Get the activities of a user on GitHub, based on the GitHub official RSS feed",
  "example": "/github/activity/DIYgod",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4823,
  "location": "activity.ts",
  "maintainers": [
    "hyoban"
  ],
  "name": "User Activities",
  "parameters": {
    "user": "GitHub username"
  },
  "path": "/activity/:user",
  "radar": [
    {
      "source": [
        "github.com/:user"
      ],
      "target": "/activity/:user"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "DIYgod's GitHub activities - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41236863782248448",
      "image": "https://avatars.githubusercontent.com/u/8266075?s=30&amp;v=4",
      "ownerUserId": null,
      "siteUrl": "https://github.com/DIYgod",
      "title": "DIYgod's GitHub activities",
      "type": "feed",
      "url": "rsshub://github/activity/DIYgod"
    },
    {
      "description": "antfu's GitHub activities - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41213691921864704",
      "image": "https://avatars.githubusercontent.com/u/11247099?s=30&amp;v=4",
      "ownerUserId": null,
      "siteUrl": "https://github.com/antfu",
      "title": "antfu's GitHub activities",
      "type": "feed",
      "url": "rsshub://github/activity/antfu"
    }
  ],
  "view": 5
}
```
