# GitHub - Repo Contributors

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/contributors/:user/:repo/:order?/:anon?`
- Route Name: `Repo Contributors`
- Example: `/github/contributors/DIYgod/RSSHub`
- URL: `github.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `zoenglinghou`
- Source Location: `contributors.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: User name
- `repo`: Repo name
- `order`: Sort order by commit numbers, desc and asc (descending by default)
- `anon`: Show anonymous users. Defaults to no, use any values for yes.


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
  - `github.com/:user/:repo/graphs/contributors`
  - `github.com/:user/:repo`
- `target`: `/contributors/:user/:repo`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/contributors/DIYgod/RSSHub",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 15,
  "location": "contributors.ts",
  "maintainers": [
    "zoenglinghou"
  ],
  "name": "Repo Contributors",
  "parameters": {
    "anon": "Show anonymous users. Defaults to no, use any values for yes.",
    "order": "Sort order by commit numbers, desc and asc (descending by default)",
    "repo": "Repo name",
    "user": "User name"
  },
  "path": "/contributors/:user/:repo/:order?/:anon?",
  "radar": [
    {
      "source": [
        "github.com/:user/:repo/graphs/contributors",
        "github.com/:user/:repo"
      ],
      "target": "/contributors/:user/:repo"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "New contributors for biquanlibai/blockchain-course - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "83173808754165760",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/biquanlibai/blockchain-course/graphs/contributors",
      "title": "biquanlibai/blockchain-course Contributors",
      "type": "feed",
      "url": "rsshub://github/contributors/biquanlibai/blockchain-course"
    },
    {
      "description": "New contributors for infiniflow/ragflow - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84430164607162368",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/infiniflow/ragflow/graphs/contributors",
      "title": "infiniflow/ragflow Contributors",
      "type": "feed",
      "url": "rsshub://github/contributors/infiniflow/ragflow"
    }
  ]
}
```
