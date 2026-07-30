# GitHub - User Starred Repositories

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/starred_repos/:user`
- Route Name: `User Starred Repositories`
- Example: `/github/starred_repos/DIYgod`
- URL: `github.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `LanceZhu`
- Source Location: `starred-repos.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: User name


## Features
- `requireConfig`: [{"description": "To get more requests", "name": "GITHUB_ACCESS_TOKEN", "optional": true}]

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
  "example": "/github/starred_repos/DIYgod",
  "features": {
    "requireConfig": [
      {
        "description": "To get more requests",
        "name": "GITHUB_ACCESS_TOKEN",
        "optional": true
      }
    ]
  },
  "heat": 142,
  "location": "starred-repos.ts",
  "maintainers": [
    "LanceZhu"
  ],
  "name": "User Starred Repositories",
  "parameters": {
    "user": "User name"
  },
  "path": "/starred_repos/:user",
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
      "description": "rcy1314's starred repositories - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "54834858065047665",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/rcy1314?tab=stars",
      "title": "rcy1314's starred repositories",
      "type": "feed",
      "url": "rsshub://github/starred_repos/rcy1314"
    },
    {
      "description": "antfu's starred repositories - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66658402653157379",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/antfu?tab=stars",
      "title": "antfu's starred repositories",
      "type": "feed",
      "url": "rsshub://github/starred_repos/antfu"
    }
  ]
}
```
