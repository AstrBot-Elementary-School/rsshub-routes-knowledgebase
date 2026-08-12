# GitHub - Repo Branches

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/branches/:user/:repo`
- Route Name: `Repo Branches`
- Example: `/github/branches/DIYgod/RSSHub`
- URL: `github.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `max-arnold`
- Source Location: `branches.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: User name
- `repo`: Repo name


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
  - `github.com/:user/:repo/branches`
  - `github.com/:user/:repo`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/branches/DIYgod/RSSHub",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 329,
  "location": "branches.ts",
  "maintainers": [
    "max-arnold"
  ],
  "name": "Repo Branches",
  "parameters": {
    "repo": "Repo name",
    "user": "User name"
  },
  "path": "/branches/:user/:repo",
  "radar": [
    {
      "source": [
        "github.com/:user/:repo/branches",
        "github.com/:user/:repo"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "ruanyf/weekly Branches - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59786436798173184",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/ruanyf/weekly/branches/all",
      "title": "ruanyf/weekly Branches",
      "type": "feed",
      "url": "rsshub://github/branches/ruanyf/weekly"
    },
    {
      "description": "kevoreilly/CAPEv2 Branches - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "104426050887270400",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/kevoreilly/CAPEv2/branches/all",
      "title": "kevoreilly/CAPEv2 Branches",
      "type": "feed",
      "url": "rsshub://github/branches/kevoreilly/CAPEv2"
    }
  ]
}
```
