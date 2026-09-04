# GitHub - Trending

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/trending/:since/:language/:spoken_language?`
- Route Name: `Trending`
- Example: `/github/trending/daily/javascript/en`
- URL: `github.com/trending`
- Language: `_None_`
- Categories: `programming, popular`
- Maintainers: `DIYgod, jameschensmith`
- Source Location: `trending.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `since`: {"description": "time range", "options": [{"label": "Today", "value": "daily"}, {"label": "This week", "value": "weekly"}, {"label": "This month", "value": "monthly"}]}
- `language`: {"default": "any", "description": "the feed language, available in [Trending page](https://github.com/trending/javascript?since=monthly) 's URL, don't filter option is `any`"}
- `spoken_language`: {"description": "natural language, available in [Trending page](https://github.com/trending/javascript?since=monthly) 's URL"}


## Features
- `requireConfig`: [{"description": "", "name": "GITHUB_ACCESS_TOKEN"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `github.com/trending`
- `target`: `/trending/:since`

## Raw JSON
```json
{
  "categories": [
    "programming",
    "popular"
  ],
  "example": "/github/trending/daily/javascript/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "GITHUB_ACCESS_TOKEN"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 65530,
  "location": "trending.tsx",
  "maintainers": [
    "DIYgod",
    "jameschensmith"
  ],
  "name": "Trending",
  "parameters": {
    "language": {
      "default": "any",
      "description": "the feed language, available in [Trending page](https://github.com/trending/javascript?since=monthly) 's URL, don't filter option is `any`"
    },
    "since": {
      "description": "time range",
      "options": [
        {
          "label": "Today",
          "value": "daily"
        },
        {
          "label": "This week",
          "value": "weekly"
        },
        {
          "label": "This month",
          "value": "monthly"
        }
      ]
    },
    "spoken_language": {
      "description": "natural language, available in [Trending page](https://github.com/trending/javascript?since=monthly) 's URL"
    }
  },
  "path": "/trending/:since/:language/:spoken_language?",
  "radar": [
    {
      "source": [
        "github.com/trending"
      ],
      "target": "/trending/:since"
    }
  ],
  "topFeeds": [
    {
      "description": "Trending repositories on GitHub today · GitHub - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41461870197170196",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/trending/?since=daily&spoken_language_code=",
      "title": "Trending repositories on GitHub today · GitHub",
      "type": "feed",
      "url": "rsshub://github/trending/daily/any"
    },
    {
      "description": "Trending repositories on GitHub this week · GitHub - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41368476124603392",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/trending/?since=weekly&spoken_language_code=",
      "title": "Trending repositories on GitHub this week · GitHub",
      "type": "feed",
      "url": "rsshub://github/trending/weekly/any"
    }
  ],
  "url": "github.com/trending",
  "view": 5
}
```
