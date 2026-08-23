# GitLab - Tags

## Coverage
`index-only`

## Route
- Namespace: `gitlab`
- Namespace Name: `GitLab`
- Route Path: `/gitlab/tag/:namespace/:project/:host?`
- Route Name: `Tags`
- Example: `/gitlab/tag/rluna-open-source%2Ffile-management%2Fowncloud/core/gitlab.com`
- URL: `gitlab.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `zoenglinghou`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `namespace`: owner or namespace. `/` needs to be replaced with `%2F`
- `project`: project name
- `host`: Gitlab instance hostname, default to gitlab.com


## Features
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/gitlab/tag/rluna-open-source%2Ffile-management%2Fowncloud/core/gitlab.com",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "tag.ts",
  "maintainers": [
    "zoenglinghou"
  ],
  "name": "Tags",
  "parameters": {
    "host": "Gitlab instance hostname, default to gitlab.com",
    "namespace": "owner or namespace. `/` needs to be replaced with `%2F`",
    "project": "project name"
  },
  "path": "/tag/:namespace/:project/:host?",
  "topFeeds": []
}
```
