# GitLab - Explore

## Coverage
`index-only`

## Route
- Namespace: `gitlab`
- Namespace Name: `GitLab`
- Route Path: `/gitlab/explore/:type?/:host?`
- Route Name: `Explore`
- Example: `/gitlab/explore/active`
- URL: `gitlab.com/explore/projects`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `imlonghao, zoenglinghou`
- Source Location: `explore.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"default": "active", "description": "Type", "options": [{"label": "Active", "value": "active"}, {"label": "Inactive", "value": "inactive"}]}
- `host`: Gitlab instance hostname, default to gitlab.com


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `gitlab.com/explore/projects/:type`
- `target`: `/explore/:type`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/gitlab/explore/active",
  "heat": 0,
  "location": "explore.ts",
  "maintainers": [
    "imlonghao",
    "zoenglinghou"
  ],
  "name": "Explore",
  "parameters": {
    "host": "Gitlab instance hostname, default to gitlab.com",
    "type": {
      "default": "active",
      "description": "Type",
      "options": [
        {
          "label": "Active",
          "value": "active"
        },
        {
          "label": "Inactive",
          "value": "inactive"
        }
      ]
    }
  },
  "path": "/explore/:type?/:host?",
  "radar": [
    {
      "source": [
        "gitlab.com/explore/projects/:type"
      ],
      "target": "/explore/:type"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "gitlab.com/explore/projects"
}
```
