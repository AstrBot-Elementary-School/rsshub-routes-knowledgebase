# Bitbucket - Commits

## Coverage
`index-only`

## Route
- Namespace: `bitbucket`
- Namespace Name: `Bitbucket`
- Route Path: `/bitbucket/commits/:workspace/:repo_slug`
- Route Name: `Commits`
- Example: `/bitbucket/commits/blaze-lib/blaze`
- URL: `bitbucket.org`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `AuroraDysis`
- Source Location: `commits.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `workspace`: Workspace
- `repo_slug`: Repository


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
  - `bitbucket.org/:workspace/:repo_slug/commits`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/bitbucket/commits/blaze-lib/blaze",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "commits.ts",
  "maintainers": [
    "AuroraDysis"
  ],
  "name": "Commits",
  "parameters": {
    "repo_slug": "Repository",
    "workspace": "Workspace"
  },
  "path": "/commits/:workspace/:repo_slug",
  "radar": [
    {
      "source": [
        "bitbucket.org/:workspace/:repo_slug/commits"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Recent Commits to blaze-lib/blaze - Powered by RSSHub",
      "errorAt": "2026-01-22T10:07:51.428Z",
      "errorMessage": "500 Internal Server Error\n",
      "id": "72530752610063360",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bitbucket.org/blaze-lib/blaze",
      "title": "Recent Commits to blaze-lib/blaze",
      "type": "feed",
      "url": "rsshub://bitbucket/commits/blaze-lib/blaze"
    }
  ]
}
```
