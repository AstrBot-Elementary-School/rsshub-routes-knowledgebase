# Threads - Search

## Coverage
`index-only`

## Route
- Namespace: `threads`
- Namespace Name: `Threads`
- Route Path: `/threads/search/:keyword/:routeParams?`
- Route Name: `Search`
- Example: `/threads/search/RSS`
- URL: `threads.net`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: Search keyword
- `routeParams`: {"description": "Extra parameters, in the format of query string. Accepts the same options as User timeline, plus:\n\n| Key         | Description | Accepts                    | Defaults to |\n| ----------- | ----------- | -------------------------- | ----------- |\n| `serpType` | Search type | `tags`/`default`/`recent` | `tags`      |"}


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/threads/search/RSS",
  "heat": 1,
  "location": "search.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Search",
  "parameters": {
    "keyword": "Search keyword",
    "routeParams": {
      "description": "Extra parameters, in the format of query string. Accepts the same options as User timeline, plus:\n\n| Key         | Description | Accepts                    | Defaults to |\n| ----------- | ----------- | -------------------------- | ----------- |\n| `serpType` | Search type | `tags`/`default`/`recent` | `tags`      |"
    }
  },
  "path": "/search/:keyword/:routeParams?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "GrokBot - Search on Threads - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1317317870085865472",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.threads.com/search?q=GrokBot&serp_type=tags",
      "title": "GrokBot - Search on Threads",
      "type": "feed",
      "url": "rsshub://threads/search/GrokBot"
    }
  ],
  "view": 1
}
```
