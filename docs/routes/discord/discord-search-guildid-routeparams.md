# Discord - Guild Search

## Coverage
`index-only`

## Route
- Namespace: `discord`
- Namespace Name: `Discord`
- Route Path: `/discord/search/:guildId/:routeParams`
- Route Name: `Guild Search`
- Example: `/discord/search/302094807046684672/content=friendly&has=image,video`
- URL: `discord.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `NekoAria`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `guildId`: Guild ID
- `routeParams`: Search parameters, support content, author_id, mentions, has, min_id, max_id, channel_id, pinned


## Features
- `requireConfig`: [{"description": "Discord authorization header", "name": "DISCORD_AUTHORIZATION"}]
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
    "social-media"
  ],
  "example": "/discord/search/302094807046684672/content=friendly&has=image,video",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "Discord authorization header",
        "name": "DISCORD_AUTHORIZATION"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "search.ts",
  "maintainers": [
    "NekoAria"
  ],
  "name": "Guild Search",
  "parameters": {
    "guildId": "Guild ID",
    "routeParams": "Search parameters, support content, author_id, mentions, has, min_id, max_id, channel_id, pinned"
  },
  "path": "/search/:guildId/:routeParams",
  "topFeeds": [
    {
      "description": "Search \"author_id:496877594676035615\" in FFXIV Mobile EN - Discord - Powered by RSSHub",
      "errorAt": "2025-11-26T09:21:26.681Z",
      "errorMessage": "Discord RSS is disabled due to the lack of authorization config\nDiscord RSS is disabled due to the lack of authorization config\n",
      "id": "168547397384130560",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://discord.com/channels/1385295224510742549",
      "title": "Search \"author_id:496877594676035615\" in FFXIV Mobile EN - Discord",
      "type": "feed",
      "url": "rsshub://discord/search/1385295224510742549/author_id=496877594676035615"
    }
  ]
}
```
