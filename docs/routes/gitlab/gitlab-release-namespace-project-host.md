# GitLab - Releases

## Coverage
`index-only`

## Route
- Namespace: `gitlab`
- Namespace Name: `GitLab`
- Route Path: `/gitlab/release/:namespace/:project/:host?`
- Route Name: `Releases`
- Example: `/gitlab/release/gitlab-org/gitlab-runner`
- URL: `gitlab.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `zoenglinghou`
- Source Location: `release.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `namespace`: owner or namespace. `/` needs to be replaced with `%2F`
- `project`: project name
- `host`: Gitlab instance hostname, default to gitlab.com


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/gitlab/release/gitlab-org/gitlab-runner",
  "heat": 0,
  "location": "release.ts",
  "maintainers": [
    "zoenglinghou"
  ],
  "name": "Releases",
  "parameters": {
    "host": "Gitlab instance hostname, default to gitlab.com",
    "namespace": "owner or namespace. `/` needs to be replaced with `%2F`",
    "project": "project name"
  },
  "path": "/release/:namespace/:project/:host?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
