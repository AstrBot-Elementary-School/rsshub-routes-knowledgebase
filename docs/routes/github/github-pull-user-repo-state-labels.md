# GitHub - Repo Pull Requests

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/pull/:user/:repo/:state?/:labels?`
- Route Name: `Repo Pull Requests`
- Example: `/github/pull/DIYgod/RSSHub`
- URL: `github.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `hashman, TonyRL`
- Source Location: `pulls.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: GitHub username
- `repo`: GitHub repo name
- `state`: {"default": "open", "description": "the state of pull requests.", "options": [{"label": "Open", "value": "open"}, {"label": "Closed", "value": "closed"}, {"label": "All", "value": "all"}]}
- `labels`: a list of comma separated label names


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
  - `github.com/:user/:repo/pulls`
  - `github.com/:user/:repo/pulls/:id`
  - `github.com/:user/:repo`
- `target`: `/pull/:user/:repo`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/pull/DIYgod/RSSHub",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 80,
  "location": "pulls.ts",
  "maintainers": [
    "hashman",
    "TonyRL"
  ],
  "name": "Repo Pull Requests",
  "parameters": {
    "labels": "a list of comma separated label names",
    "repo": "GitHub repo name",
    "state": {
      "default": "open",
      "description": "the state of pull requests.",
      "options": [
        {
          "label": "Open",
          "value": "open"
        },
        {
          "label": "Closed",
          "value": "closed"
        },
        {
          "label": "All",
          "value": "all"
        }
      ]
    },
    "user": "GitHub username"
  },
  "path": "/pull/:user/:repo/:state?/:labels?",
  "radar": [
    {
      "source": [
        "github.com/:user/:repo/pulls",
        "github.com/:user/:repo/pulls/:id",
        "github.com/:user/:repo"
      ],
      "target": "/pull/:user/:repo"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "RSSNext/Follow Open Pull Requests - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "77720830590388224",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/RSSNext/Follow/pulls",
      "title": "RSSNext/Follow Open Pull Requests",
      "type": "feed",
      "url": "rsshub://github/pull/RSSNext/Follow"
    },
    {
      "description": "projectdiscovery/nuclei-templates Open Pull Requests - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "154479685635981317",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/projectdiscovery/nuclei-templates/pulls",
      "title": "projectdiscovery/nuclei-templates Open Pull Requests",
      "type": "feed",
      "url": "rsshub://github/pull/projectdiscovery/nuclei-templates"
    }
  ]
}
```
