# Discord - Channel Messages

## Coverage
`index-only`

## Route
- Namespace: `discord`
- Namespace Name: `Discord`
- Route Path: `/discord/channel/:channelId`
- Route Name: `Channel Messages`
- Example: `/discord/channel/950465850056536084`
- URL: `discord.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `channelId`: Channel ID


## Features
- `requireConfig`: [{"description": "Discord authorization header from the browser", "name": "DISCORD_AUTHORIZATION"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `discord.com/channels/:guildId/:channelId/:messageID`
  - `discord.com/channels/:guildId/:channelId`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/discord/channel/950465850056536084",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "Discord authorization header from the browser",
        "name": "DISCORD_AUTHORIZATION"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 50,
  "location": "channel.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Channel Messages",
  "parameters": {
    "channelId": "Channel ID"
  },
  "path": "/channel/:channelId",
  "radar": [
    {
      "source": [
        "discord.com/channels/:guildId/:channelId/:messageID",
        "discord.com/channels/:guildId/:channelId"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "#💬｜讨论 - Folo - Discord - Powered by RSSHub",
      "errorAt": "2025-12-04T20:07:28.537Z",
      "errorMessage": "Discord RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#route-specific-configurations\">relevant config</a>\nDiscord RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#route-specific-configurations\">relevant config</a>\nDiscord RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#route-specific-configurations\">relevant config</a>\n",
      "id": "97899189022799872",
      "image": "https://cdn.discordapp.com/icons/1243823539426033696/b7e6b0a2026084252f2ccb46b824c31e.webp",
      "ownerUserId": null,
      "siteUrl": "https://discord.com/channels/1243823539426033696/1265925366820765818",
      "title": "#💬｜讨论 - Folo - Discord",
      "type": "feed",
      "url": "rsshub://discord/channel/1265925366820765818"
    },
    {
      "description": "#📢｜announcements - Folo - Discord - Powered by RSSHub",
      "errorAt": "2025-12-11T16:02:11.838Z",
      "errorMessage": "Discord RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#route-specific-configurations\">relevant config</a>\nDiscord RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#route-specific-configurations\">relevant config</a>\n",
      "id": "94583394560561152",
      "image": "https://cdn.discordapp.com/icons/1243823539426033696/b7e6b0a2026084252f2ccb46b824c31e.webp",
      "ownerUserId": null,
      "siteUrl": "https://discord.com/channels/1243823539426033696/1265924538747715735",
      "title": "#📢｜announcements - Folo - Discord",
      "type": "feed",
      "url": "rsshub://discord/channel/1265924538747715735"
    }
  ]
}
```
