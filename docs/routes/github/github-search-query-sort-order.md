# GitHub - Search Result

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/search/:query/:sort?/:order?`
- Route Name: `Search Result`
- Example: `/github/search/RSSHub/bestmatch/desc`
- URL: `github.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `LogicJake`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
| Sort options     | sort      |
| ---------------- | --------- |
| Best match       | bestmatch |
| Most stars       | stars     |
| Most forks       | forks     |
| Recently updated | updated   |

## Parameters
- `query`: search keyword
- `sort`: Sort options (default to bestmatch)
- `order`: Sort order, desc and asc (desc descending by default)


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| Sort options     | sort      |\n| ---------------- | --------- |\n| Best match       | bestmatch |\n| Most stars       | stars     |\n| Most forks       | forks     |\n| Recently updated | updated   |",
  "example": "/github/search/RSSHub/bestmatch/desc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 39,
  "location": "search.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "Search Result",
  "parameters": {
    "order": "Sort order, desc and asc (desc descending by default)",
    "query": "search keyword",
    "sort": "Sort options (default to bestmatch)"
  },
  "path": "/search/:query/:sort?/:order?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "ComfyUI的搜索结果 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "133953344935277568",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/search?o=desc&q=ComfyUI&s=updated&type=Repositories",
      "title": "ComfyUI的搜索结果",
      "type": "feed",
      "url": "rsshub://github/search/ComfyUI/updated/desc"
    },
    {
      "description": "backdoorattack的搜索结果 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "139683019365314560",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/search?o=desc&q=backdoorattack&s=updated&type=Repositories",
      "title": "backdoorattack的搜索结果",
      "type": "feed",
      "url": "rsshub://github/search/backdoorattack/updated/desc"
    }
  ]
}
```
