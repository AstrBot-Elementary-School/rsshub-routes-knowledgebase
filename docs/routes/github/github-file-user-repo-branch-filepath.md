# GitHub - File Commits

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/file/:user/:repo/:branch/:filepath{.+}`
- Route Name: `File Commits`
- Example: `/github/file/DIYgod/RSSHub/master/README.md`
- URL: `github.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `zengxs`
- Source Location: `file.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: GitHub user or org name
- `repo`: repository name
- `branch`: branch name
- `filepath`: path of target file


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `github.com/:user/:repo/blob/:branch/*filepath`
- `target`: `/file/:user/:repo/:branch/:filepath`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/file/DIYgod/RSSHub/master/README.md",
  "heat": 179,
  "location": "file.ts",
  "maintainers": [
    "zengxs"
  ],
  "name": "File Commits",
  "parameters": {
    "branch": "branch name",
    "filepath": "path of target file",
    "repo": "repository name",
    "user": "GitHub user or org name"
  },
  "path": "/file/:user/:repo/:branch/:filepath{.+}",
  "radar": [
    {
      "source": [
        "github.com/:user/:repo/blob/:branch/*filepath"
      ],
      "target": "/file/:user/:repo/:branch/:filepath"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "GitHub File - guanguans/favorite-link/master/README.md - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55788057182175233",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/guanguans/favorite-link/commits/master/README.md",
      "title": "GitHub File - guanguans/favorite-link/master/README.md",
      "type": "feed",
      "url": "rsshub://github/file/guanguans/favorite-link/master/README.md"
    },
    {
      "description": "GitHub File - anthropics/claude-code/main/CHANGELOG.md - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "160510153923355648",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/anthropics/claude-code/commits/main/CHANGELOG.md",
      "title": "GitHub File - anthropics/claude-code/main/CHANGELOG.md",
      "type": "feed",
      "url": "rsshub://github/file/anthropics/claude-code/main/CHANGELOG.md"
    }
  ]
}
```
