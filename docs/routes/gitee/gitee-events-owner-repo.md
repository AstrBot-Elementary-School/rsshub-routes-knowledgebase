# Gitee - 仓库动态

## Coverage
`index-only`

## Route
- Namespace: `gitee`
- Namespace Name: `Gitee`
- Route Path: `/gitee/events/:owner/:repo`
- Route Name: `仓库动态`
- Example: `/gitee/events/y_project/RuoYi`
- URL: `gitee.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `TonyRL`
- Source Location: `repos/events.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `owner`: 用户名
- `repo`: 仓库名


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
  - `gitee.com/:owner/:repo`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/gitee/events/y_project/RuoYi",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 15,
  "location": "repos/events.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "仓库动态",
  "parameters": {
    "owner": "用户名",
    "repo": "仓库名"
  },
  "path": "/events/:owner/:repo",
  "radar": [
    {
      "source": [
        "gitee.com/:owner/:repo"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "yhArcadia/Yunzai-Bot-plugins-index - 仓库动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "83741276078048256",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gitee.com/yhArcadia/Yunzai-Bot-plugins-index",
      "title": "yhArcadia/Yunzai-Bot-plugins-index - 仓库动态",
      "type": "feed",
      "url": "rsshub://gitee/events/yhArcadia/Yunzai-Bot-plugins-index"
    },
    {
      "description": "labuladong/fucking-algorithm - 仓库动态 - Powered by RSSHub",
      "errorAt": "2026-07-12T02:04:12.308Z",
      "errorMessage": "Cannot read properties of null (reading 'login')\n",
      "id": "165023100116440064",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gitee.com/labuladong/fucking-algorithm",
      "title": "labuladong/fucking-algorithm - 仓库动态",
      "type": "feed",
      "url": "rsshub://gitee/events/labuladong/fucking-algorithm"
    }
  ]
}
```
