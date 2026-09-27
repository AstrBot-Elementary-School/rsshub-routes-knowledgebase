# GitHub - User Repo

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/repos/:user/:type?/:sort?`
- Route Name: `User Repo`
- Example: `/github/repos/DIYgod`
- URL: `github.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `DIYgod`
- Source Location: `repos.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: GitHub username
- `type`: Type of repository, can be `all`, `owner`, `member`, `public`, `private`, `forks`, `sources`
- `sort`: Sort by `created`, `updated`, `pushed`, `full_name`


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

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/repos/DIYgod",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 224,
  "location": "repos.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "User Repo",
  "parameters": {
    "sort": "Sort by `created`, `updated`, `pushed`, `full_name`",
    "type": "Type of repository, can be `all`, `owner`, `member`, `public`, `private`, `forks`, `sources`",
    "user": "GitHub username"
  },
  "path": "/repos/:user/:type?/:sort?",
  "radar": [
    {
      "source": [
        "github.com/:user"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Quorafind's GitHub repositories - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59462968084103174",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/Quorafind",
      "title": "Quorafind's GitHub repositories",
      "type": "feed",
      "url": "rsshub://github/repos/Quorafind"
    },
    {
      "description": "ZHO-ZHO-ZHO's GitHub repositories - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "135939109364459520",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/ZHO-ZHO-ZHO",
      "title": "ZHO-ZHO-ZHO's GitHub repositories",
      "type": "feed",
      "url": "rsshub://github/repos/ZHO-ZHO-ZHO"
    }
  ]
}
```
