# GitHub - Gist Commits

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/gist/:gistId`
- Route Name: `Gist Commits`
- Example: `/github/gist/d2c152bb7179d07015f336b1a0582679`
- URL: `github.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `TonyRL`
- Source Location: `gist.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `gistId`: Gist ID


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
  - `gist.github.com/:owner/:gistId/revisions`
  - `gist.github.com/:owner/:gistId/stargazers`
  - `gist.github.com/:owner/:gistId/forks`
  - `gist.github.com/:owner/:gistId`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/gist/d2c152bb7179d07015f336b1a0582679",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 30,
  "location": "gist.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Gist Commits",
  "parameters": {
    "gistId": "Gist ID"
  },
  "path": "/gist/:gistId",
  "radar": [
    {
      "source": [
        "gist.github.com/:owner/:gistId/revisions",
        "gist.github.com/:owner/:gistId/stargazers",
        "gist.github.com/:owner/:gistId/forks",
        "gist.github.com/:owner/:gistId"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "The Most Popular Blogs of Hacker News in 2025 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "241120420735285248",
      "image": "https://avatars.githubusercontent.com/u/3262610?v=4",
      "ownerUserId": null,
      "siteUrl": "https://gist.github.com/emschwartz/e6d2bf860ccc367fe37ff953ba6de66b/revisions",
      "title": "emschwartz / README.md",
      "type": "feed",
      "url": "rsshub://github/gist/e6d2bf860ccc367fe37ff953ba6de66b"
    },
    {
      "description": "JavDB top 250 movies list. [Updated on 2026/01] - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70188043280184320",
      "image": "https://avatars.githubusercontent.com/u/101241777?v=4",
      "ownerUserId": null,
      "siteUrl": "https://gist.github.com/jinjier/7a405fad753f996d85ed43073e3bf009/revisions",
      "title": "jinjier / javdb-top250.md",
      "type": "feed",
      "url": "rsshub://github/gist/7a405fad753f996d85ed43073e3bf009"
    }
  ]
}
```
