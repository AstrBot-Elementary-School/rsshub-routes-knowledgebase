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
      "description": "New contributors for PixarAnimationStudios/OpenUSD - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84958270281030656",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/PixarAnimationStudios/OpenUSD/graphs/contributors",
      "title": "PixarAnimationStudios/OpenUSD Contributors",
      "type": "feed",
      "url": "rsshub://github/contributors/PixarAnimationStudios/OpenUSD"
    },
    {
      "description": "New contributors for cgw88/cgw321.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "162529901506768896",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/cgw88/cgw321.com/graphs/contributors",
      "title": "cgw88/cgw321.com Contributors",
      "type": "feed",
      "url": "rsshub://github/contributors/cgw88/cgw321.com"
    }
  ]
}
```
