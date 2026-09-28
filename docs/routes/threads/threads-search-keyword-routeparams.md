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
  "heat": 0,
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
    "code": 1,
    "message": "AssertionError: expected [ …(15) ] to not include 'https://www.threads.com/t/DdtVubCge00'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "view": 1
}
```
