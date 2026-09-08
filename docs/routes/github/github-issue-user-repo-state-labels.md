# GitHub - Repo Issues

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/issue/:user/:repo/:state?/:labels?`
- Route Name: `Repo Issues`
- Example: `/github/issue/DIYgod/RSSHub/open`
- URL: `github.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `HenryQW, AndreyMZ`
- Source Location: `issue.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: GitHub username
- `repo`: GitHub repo name
- `state`: {"default": "open", "description": "the state of the issues.", "options": [{"label": "Open", "value": "open"}, {"label": "Closed", "value": "closed"}, {"label": "All", "value": "all"}]}
- `labels`: a list of comma separated label names


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `github.com/:user/:repo/issues`
  - `github.com/:user/:repo/issues/:id`
  - `github.com/:user/:repo`
- `target`: `/issue/:user/:repo`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/issue/DIYgod/RSSHub/open",
  "heat": 625,
  "location": "issue.ts",
  "maintainers": [
    "HenryQW",
    "AndreyMZ"
  ],
  "name": "Repo Issues",
  "parameters": {
    "labels": "a list of comma separated label names",
    "repo": "GitHub repo name",
    "state": {
      "default": "open",
      "description": "the state of the issues.",
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
  "path": "/issue/:user/:repo/:state?/:labels?",
  "radar": [
    {
      "source": [
        "github.com/:user/:repo/issues",
        "github.com/:user/:repo/issues/:id",
        "github.com/:user/:repo"
      ],
      "target": "/issue/:user/:repo"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "ruanyf/weekly Issues - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "52721325092269113",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/ruanyf/weekly/issues",
      "title": "ruanyf/weekly Issues",
      "type": "feed",
      "url": "rsshub://github/issue/ruanyf/weekly"
    },
    {
      "description": "Geekhyt/weekly Issues - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "53505290474416128",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/Geekhyt/weekly/issues",
      "title": "Geekhyt/weekly Issues",
      "type": "feed",
      "url": "rsshub://github/issue/Geekhyt/weekly"
    }
  ],
  "view": 5
}
```
