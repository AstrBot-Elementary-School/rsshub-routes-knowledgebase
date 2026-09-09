# Minecraft - Java Blocked Servers

## Coverage
`index-only`

## Route
- Namespace: `minecraft`
- Namespace Name: `Minecraft`
- Route Path: `/minecraft/blockedservers`
- Route Name: `Java Blocked Servers`
- Example: `/minecraft/blockedservers`
- URL: `minecraft.net/`
- Language: `_None_`
- Categories: `game`
- Maintainers: `xtexChooser`
- Source Location: `blockedservers.ts`
- Source Module: `_None_`

## Description
Java 版中被 Mojang 通过 sessionserver 阻止的服务器域名的 SHA-1 散列

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `minecraft.net/`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "Java 版中被 Mojang 通过 sessionserver 阻止的服务器域名的 SHA-1 散列",
  "example": "/minecraft/blockedservers",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "blockedservers.ts",
  "maintainers": [
    "xtexChooser"
  ],
  "name": "Java Blocked Servers",
  "parameters": {},
  "path": "/blockedservers",
  "radar": [
    {
      "source": [
        "minecraft.net/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Minecraft Java版被阻止的服务器域名散列 - Powered by RSSHub",
      "errorAt": "2026-09-07T13:25:56.684Z",
      "errorMessage": "[GET] \"https://sessionserver.mojang.com/blockedservers\": 403 Forbidden\n",
      "id": "164180081436038144",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sessionserver.mojang.com/blockedservers",
      "title": "Minecraft Java版被阻止的服务器域名散列",
      "type": "feed",
      "url": "rsshub://minecraft/blockedservers"
    }
  ],
  "url": "minecraft.net/",
  "zh": {
    "name": "Java版被阻止的服务器域名散列"
  }
}
```
