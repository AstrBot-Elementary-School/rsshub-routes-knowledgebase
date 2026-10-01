# Gitstar Ranking - Ranking

## Coverage
`index-only`

## Route
- Namespace: `gitstar-ranking`
- Namespace Name: `Gitstar Ranking`
- Route Path: `/gitstar-ranking/:category?`
- Route Name: `Ranking`
- Example: `/gitstar-ranking/repositories`
- URL: `gitstar-ranking.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
::: tip
To subscribe to [Repositories](https://gitstar-ranking.com/repositories), where the source URL is `https://gitstar-ranking.com/repositories`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/gitstar-ranking/repositories`](https://rsshub.app/gitstar-ranking/repositories).
:::

| Category                                                   | ID                                                                |
| ---------------------------------------------------------- | ----------------------------------------------------------------- |
| [Users](https://gitstar-ranking.com/users)                 | [users](https://rsshub.app/gitstar-ranking/users)                 |
| [Organizations](https://gitstar-ranking.com/organizations) | [organizations](https://rsshub.app/gitstar-ranking/organizations) |
| [Repositories](https://gitstar-ranking.com/repositories)   | [repositories](https://rsshub.app/gitstar-ranking/repositories)   |

## Parameters
- `category`: {"description": "Category, Repositories by default", "options": [{"label": "Users", "value": "users"}, {"label": "Organizations", "value": "organizations"}, {"label": "Repositories", "value": "repositories"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `gitstar-ranking.com/:category`
- `target`: `/:category`
### Rule 2
- `title`: `Users`
- `source`:
  - `gitstar-ranking.com/users`
- `target`: `/users`
### Rule 3
- `title`: `Organizations`
- `source`:
  - `gitstar-ranking.com/organizations`
- `target`: `/organizations`
### Rule 4
- `title`: `Repositories`
- `source`:
  - `gitstar-ranking.com/repositories`
- `target`: `/repositories`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "::: tip\nTo subscribe to [Repositories](https://gitstar-ranking.com/repositories), where the source URL is `https://gitstar-ranking.com/repositories`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/gitstar-ranking/repositories`](https://rsshub.app/gitstar-ranking/repositories).\n:::\n\n| Category                                                   | ID                                                                |\n| ---------------------------------------------------------- | ----------------------------------------------------------------- |\n| [Users](https://gitstar-ranking.com/users)                 | [users](https://rsshub.app/gitstar-ranking/users)                 |\n| [Organizations](https://gitstar-ranking.com/organizations) | [organizations](https://rsshub.app/gitstar-ranking/organizations) |\n| [Repositories](https://gitstar-ranking.com/repositories)   | [repositories](https://rsshub.app/gitstar-ranking/repositories)   |",
  "example": "/gitstar-ranking/repositories",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 11,
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Ranking",
  "parameters": {
    "category": {
      "description": "Category, Repositories by default",
      "options": [
        {
          "label": "Users",
          "value": "users"
        },
        {
          "label": "Organizations",
          "value": "organizations"
        },
        {
          "label": "Repositories",
          "value": "repositories"
        }
      ]
    }
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "gitstar-ranking.com/:category"
      ],
      "target": "/:category"
    },
    {
      "source": [
        "gitstar-ranking.com/users"
      ],
      "target": "/users",
      "title": "Users"
    },
    {
      "source": [
        "gitstar-ranking.com/organizations"
      ],
      "target": "/organizations",
      "title": "Organizations"
    },
    {
      "source": [
        "gitstar-ranking.com/repositories"
      ],
      "target": "/repositories",
      "title": "Repositories"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Repositories Ranking - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "195998401576375296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gitstar-ranking.com/repositories",
      "title": "Repositories Ranking - Gitstar Ranking",
      "type": "feed",
      "url": "rsshub://gitstar-ranking"
    },
    {
      "description": "Repositories Ranking - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "183008047351892992",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gitstar-ranking.com/repositories",
      "title": "Repositories Ranking - Gitstar Ranking",
      "type": "feed",
      "url": "rsshub://gitstar-ranking/repositories"
    }
  ],
  "url": "gitstar-ranking.com",
  "view": 0
}
```
