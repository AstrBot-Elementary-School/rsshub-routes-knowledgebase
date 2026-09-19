# GitHub - Wiki History

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/wiki/:user/:repo/:page?`
- Route Name: `Wiki History`
- Example: `/github/wiki/flutter/flutter/Roadmap`
- URL: `github.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `TonyRL`
- Source Location: `wiki.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: User / Org name
- `repo`: Repo name
- `page`: Page slug, can be found in URL, empty means Home


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
  - `github.com/:user/:repo/wiki/:page/_history`
  - `github.com/:user/:repo/wiki/:page`
  - `github.com/:user/:repo/wiki/_history`
  - `github.com/:user/:repo/wiki`
- `target`: `/wiki/:user/:repo/:page`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/wiki/flutter/flutter/Roadmap",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 23,
  "location": "wiki.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Wiki History",
  "parameters": {
    "page": "Page slug, can be found in URL, empty means Home",
    "repo": "Repo name",
    "user": "User / Org name"
  },
  "path": "/wiki/:user/:repo/:page?",
  "radar": [
    {
      "source": [
        "github.com/:user/:repo/wiki/:page/_history",
        "github.com/:user/:repo/wiki/:page",
        "github.com/:user/:repo/wiki/_history",
        "github.com/:user/:repo/wiki"
      ],
      "target": "/wiki/:user/:repo/:page"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "History / ss免费账号 - Alvin9999/new-pac - Powered by RSSHub",
      "errorAt": "2025-12-19T04:11:54.884Z",
      "errorMessage": "[GET] \"https://github.com/Alvin9999/new-pac/wiki/ss免费账号/_history\": 404 Not Found\n",
      "id": "76074281958260736",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/Alvin9999/new-pac/wiki/ss%E5%85%8D%E8%B4%B9%E8%B4%A6%E5%8F%B7/_history",
      "title": "History / ss免费账号 - Alvin9999/new-pac",
      "type": "feed",
      "url": "rsshub://github/wiki/Alvin9999/new-pac/ss%E5%85%8D%E8%B4%B9%E8%B4%A6%E5%8F%B7"
    },
    {
      "description": "History / v2ray免费账号 - Alvin9999/new-pac - Powered by RSSHub",
      "errorAt": "2025-12-19T04:17:08.051Z",
      "errorMessage": "[GET] \"https://github.com/Alvin9999/new-pac/wiki/v2ray免费账号/_history\": 404 Not Found\n",
      "id": "80275611650670592",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/Alvin9999/new-pac/wiki/v2ray%E5%85%8D%E8%B4%B9%E8%B4%A6%E5%8F%B7/_history",
      "title": "History / v2ray免费账号 - Alvin9999/new-pac",
      "type": "feed",
      "url": "rsshub://github/wiki/Alvin9999/new-pac/v2ray%E5%85%8D%E8%B4%B9%E8%B4%A6%E5%8F%B7"
    }
  ]
}
```
