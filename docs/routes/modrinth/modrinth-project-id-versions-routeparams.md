# Modrinth - Project versions

## Coverage
`index-only`

## Route
- Namespace: `modrinth`
- Namespace Name: `Modrinth`
- Route Path: `/modrinth/project/:id/versions/:routeParams?`
- Route Name: `Project versions`
- Example: `/modrinth/project/sodium/versions`
- URL: `modrinth.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `SettingDust`
- Source Location: `versions.tsx`
- Source Module: `_None_`

## Description
| Name           | Example                                      |
| -------------- | -------------------------------------------- |
| loaders        | loaders=fabric\&loaders=quilt\&loaders=forge |
| game\_versions | game\_versions=1.20.1\&game\_versions=1.20.2 |
| featured       | featured=true                                |

## Parameters
- `id`: Id or slug of the Modrinth project
- `routeParams`: Extra route params. See the table below for options


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
  - `modrinth.com/mod/:id/*`
  - `modrinth.com/plugin/:id/*`
  - `modrinth.com/datapack/:id/*`
  - `modrinth.com/shader/:id/*`
  - `modrinth.com/resourcepack/:id/*`
  - `modrinth.com/modpack/:id/*`
  - `modrinth.com/mod/:id`
  - `modrinth.com/plugin/:id`
  - `modrinth.com/datapack/:id`
  - `modrinth.com/shader/:id`
  - `modrinth.com/resourcepack/:id`
  - `modrinth.com/modpack/:id`
- `target`: `/project/:id/versions`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| Name           | Example                                      |\n| -------------- | -------------------------------------------- |\n| loaders        | loaders=fabric\\&loaders=quilt\\&loaders=forge |\n| game\\_versions | game\\_versions=1.20.1\\&game\\_versions=1.20.2 |\n| featured       | featured=true                                |",
  "example": "/modrinth/project/sodium/versions",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 35,
  "location": "versions.tsx",
  "maintainers": [
    "SettingDust"
  ],
  "name": "Project versions",
  "parameters": {
    "id": "Id or slug of the Modrinth project",
    "routeParams": "Extra route params. See the table below for options"
  },
  "path": "/project/:id/versions/:routeParams?",
  "radar": [
    {
      "source": [
        "modrinth.com/mod/:id/*",
        "modrinth.com/plugin/:id/*",
        "modrinth.com/datapack/:id/*",
        "modrinth.com/shader/:id/*",
        "modrinth.com/resourcepack/:id/*",
        "modrinth.com/modpack/:id/*",
        "modrinth.com/mod/:id",
        "modrinth.com/plugin/:id",
        "modrinth.com/datapack/:id",
        "modrinth.com/shader/:id",
        "modrinth.com/resourcepack/:id",
        "modrinth.com/modpack/:id"
      ],
      "target": "/project/:id/versions"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Aesthetic Technology that empowers the Player - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "88557710935450624",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://modrinth.com/project/create",
      "title": "Create Modrinth versions",
      "type": "feed",
      "url": "rsshub://modrinth/project/create/versions"
    },
    {
      "description": "An all-in-one solution that works - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "123852430344537088",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://modrinth.com/project/gG7VFbG0",
      "title": "TAB Modrinth versions",
      "type": "feed",
      "url": "rsshub://modrinth/project/gG7VFbG0/versions"
    }
  ]
}
```
