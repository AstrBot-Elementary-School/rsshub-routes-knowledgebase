# itch.io - Developer Logs

## Coverage
`index-only`

## Route
- Namespace: `itch`
- Namespace Name: `itch.io`
- Route Path: `/itch/devlog/:user/:id`
- Route Name: `Developer Logs`
- Example: `/itch/devlog/teamterrible/the-baby-in-yellow`
- URL: `itch.io`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `devlog.ts`
- Source Module: `_None_`

## Description
`User id` is the field before `.itch.io` in the URL of the corresponding page, e.g. the URL of [The Baby In Yellow Devlog](https://teamterrible.itch.io/the-baby-in-yellow/devlog) is `https://teamterrible.itch.io/the-baby-in-yellow/devlog`, where the field before `.itch.io` is `teamterrible`.

`Item id` is the field between `itch.io` and `/devlog` in the URL of the corresponding page, e.g. the URL for [The Baby In Yellow Devlog](https://teamterrible.itch.io/the-baby-in-yellow/devlog) is `https://teamterrible.itch.io/the-baby-in-yellow/devlog`, where the field between `itch.io` and `/devlog` is `the-baby-in-yellow`.

So the route is [`/itch/devlogs/teamterrible/the-baby-in-yellow`](https://rsshub.app/itch/devlogs/teamterrible/the-baby-in-yellow).

## Parameters
- `user`: User id, can be found in URL
- `id`: Item id, can be found in URL


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
    "game"
  ],
  "description": "`User id` is the field before `.itch.io` in the URL of the corresponding page, e.g. the URL of [The Baby In Yellow Devlog](https://teamterrible.itch.io/the-baby-in-yellow/devlog) is `https://teamterrible.itch.io/the-baby-in-yellow/devlog`, where the field before `.itch.io` is `teamterrible`.\n\n`Item id` is the field between `itch.io` and `/devlog` in the URL of the corresponding page, e.g. the URL for [The Baby In Yellow Devlog](https://teamterrible.itch.io/the-baby-in-yellow/devlog) is `https://teamterrible.itch.io/the-baby-in-yellow/devlog`, where the field between `itch.io` and `/devlog` is `the-baby-in-yellow`.\n\nSo the route is [`/itch/devlogs/teamterrible/the-baby-in-yellow`](https://rsshub.app/itch/devlogs/teamterrible/the-baby-in-yellow).",
  "example": "/itch/devlog/teamterrible/the-baby-in-yellow",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 12,
  "location": "devlog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Developer Logs",
  "parameters": {
    "id": "Item id, can be found in URL",
    "user": "User id, can be found in URL"
  },
  "path": "/devlog/:user/:id",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Devlog - Agent17 (18+ Adult Game) by HEXATAIL - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "81600518557769728",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hexatail.itch.io/agent17/devlog",
      "title": "Devlog - Agent17 (18+ Adult Game) by HEXATAIL",
      "type": "feed",
      "url": "rsshub://itch/devlog/hexatail/agent17"
    },
    {
      "description": "Devlog - Eternum by Caribdis - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "81598929713485824",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://caribdis.itch.io/eternum/devlog",
      "title": "Devlog - Eternum by Caribdis",
      "type": "feed",
      "url": "rsshub://itch/devlog/caribdis/eternum"
    }
  ]
}
```
