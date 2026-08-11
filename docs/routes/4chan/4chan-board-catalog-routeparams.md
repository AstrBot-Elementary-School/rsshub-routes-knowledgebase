# 4chan - Board's catalog

## Coverage
`index-only`

## Route
- Namespace: `4chan`
- Namespace Name: `4chan`
- Route Path: `/4chan/:board/catalog/:routeParams?`
- Route Name: `Board's catalog`
- Example: `/4chan/g/catalog`
- URL: `4chan.org`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `heisenshark`
- Source Location: `catalog.tsx`
- Source Module: `_None_`

## Description
Specify options (in the format of query string) in parameter `routeParams` to control extra features for threads

| Key               | Description                                      | Accepts                | Defaults to |
| ----------------- | ------------------------------------------------ | ---------------------- | ----------- |
| `showReplyCount`  | Show number of replies of each thread in catalog | `0`/`1`/`true`/`false` | `false`     |
| `showLastReplies` | Show last 5 replies of each thread               | `0`/`1`/`true`/`false` | `false`     |
| `revealSpoilers`  | Don't wrap images tagged as spoilers             | `0`/`1`/`true`/`false` | `false`     |
| `excludeSticky`   | Filter out sticky threads                        | `0`/`1`/`true`/`false` | `false`     |
| `minReplies`      | Minimum replies per thread                       | Integer                | None        |
| `maxReplies`      | Maximum replies per thread                       | Integer                | None        |

## Parameters
- `board`: 4chan board
- `routeParams`: extra parameters, see the table above


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `boards.4chan.org/:board/`
- `target`: `/:board/catalog`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "Specify options (in the format of query string) in parameter `routeParams` to control extra features for threads\n\n| Key               | Description                                      | Accepts                | Defaults to |\n| ----------------- | ------------------------------------------------ | ---------------------- | ----------- |\n| `showReplyCount`  | Show number of replies of each thread in catalog | `0`/`1`/`true`/`false` | `false`     |\n| `showLastReplies` | Show last 5 replies of each thread               | `0`/`1`/`true`/`false` | `false`     |\n| `revealSpoilers`  | Don't wrap images tagged as spoilers             | `0`/`1`/`true`/`false` | `false`     |\n| `excludeSticky`   | Filter out sticky threads                        | `0`/`1`/`true`/`false` | `false`     |\n| `minReplies`      | Minimum replies per thread                       | Integer                | None        |\n| `maxReplies`      | Maximum replies per thread                       | Integer                | None        |",
  "example": "/4chan/g/catalog",
  "features": {
    "antiCrawler": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "catalog.tsx",
  "maintainers": [
    "heisenshark"
  ],
  "name": "Board's catalog",
  "parameters": {
    "board": "4chan board",
    "routeParams": "extra parameters, see the table above"
  },
  "path": "/:board/catalog/:routeParams?",
  "radar": [
    {
      "source": [
        "boards.4chan.org/:board/"
      ],
      "target": "/:board/catalog"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "4chan's /hc/ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "257165880547653632",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://boards.4chan.org/hc/catalog",
      "title": "4chan's /hc/",
      "type": "feed",
      "url": "rsshub://4chan/hc/catalog"
    },
    {
      "description": "4chan's /r/ - Powered by RSSHub",
      "errorAt": "2026-06-05T08:02:48.597Z",
      "errorMessage": "[GET] \"https://a.4cdn.org/r/catalog.json\": 404 Not Found\n",
      "id": "257165688284952576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://boards.4chan.org/r/catalog",
      "title": "4chan's /r/",
      "type": "feed",
      "url": "rsshub://4chan/r/catalog"
    }
  ]
}
```
