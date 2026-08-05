# GitHub - Repo Stars

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/stars/:user/:repo`
- Route Name: `Repo Stars`
- Example: `/github/stars/DIYgod/RSSHub`
- URL: `github.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `HenryQW`
- Source Location: `star.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: GitHub username
- `repo`: GitHub repo name


## Features
- `requireConfig`: [{"description": "GitHub Access Token", "name": "GITHUB_ACCESS_TOKEN"}]

## Radar
### Rule 1
- `source`:
  - `github.com/:user/:repo/stargazers`
  - `github.com/:user/:repo`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/stars/DIYgod/RSSHub",
  "features": {
    "requireConfig": [
      {
        "description": "GitHub Access Token",
        "name": "GITHUB_ACCESS_TOKEN"
      }
    ]
  },
  "heat": 151,
  "location": "star.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "Repo Stars",
  "parameters": {
    "repo": "GitHub repo name",
    "user": "GitHub username"
  },
  "path": "/stars/:user/:repo",
  "radar": [
    {
      "source": [
        "github.com/:user/:repo/stargazers",
        "github.com/:user/:repo"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "DIYgod/RSSHub’s stargazers - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59555499555782656",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/DIYgod/RSSHub/stargazers",
      "title": "DIYgod/RSSHub’s stargazers",
      "type": "feed",
      "url": "rsshub://github/stars/DIYgod/RSSHub"
    },
    {
      "description": "abel533/Mapper’s stargazers - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63414516945456128",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/abel533/Mapper/stargazers",
      "title": "abel533/Mapper’s stargazers",
      "type": "feed",
      "url": "rsshub://github/stars/abel533/Mapper"
    }
  ],
  "view": 5
}
```
