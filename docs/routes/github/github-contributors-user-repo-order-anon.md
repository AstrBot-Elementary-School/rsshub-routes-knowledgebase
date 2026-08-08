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
      "description": "New contributors for zabbix/zabbix-docker - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "95485494519570432",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/zabbix/zabbix-docker/graphs/contributors",
      "title": "zabbix/zabbix-docker Contributors",
      "type": "feed",
      "url": "rsshub://github/contributors/zabbix/zabbix-docker"
    },
    {
      "description": "New contributors for limbopro/Adblock4limbo - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "126804218589762560",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/limbopro/Adblock4limbo/graphs/contributors",
      "title": "limbopro/Adblock4limbo Contributors",
      "type": "feed",
      "url": "rsshub://github/contributors/limbopro/Adblock4limbo"
    }
  ]
}
```
