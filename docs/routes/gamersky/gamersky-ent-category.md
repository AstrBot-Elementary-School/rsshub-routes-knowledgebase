# GamerSky - 娱乐

## Coverage
`index-only`

## Route
- Namespace: `gamersky`
- Namespace Name: `GamerSky`
- Route Path: `/gamersky/ent/:category?`
- Route Name: `娱乐`
- Example: `/gamersky/ent/xz`
- URL: `gamersky.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `LogicJake`
- Source Location: `ent.ts`
- Source Module: `_None_`

## Description
|all|qw|movie|discovery|wp|wenku|xz|
|---|---|---|---|---|---|---|
|热点图文|趣囧时间|游民影院|游观天下|壁纸图库|游民盘点|游民福利|

## Parameters
- `type`: 分类类型，留空为 `all`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `title`: `热点图文`
- `source`:
  - `www.gamersky.com/ent`
- `target`: `/ent/all`
### Rule 2
- `title`: `趣囧时间`
- `source`:
  - `www.gamersky.com/ent/qw`
- `target`: `/ent/qw`
### Rule 3
- `title`: `游民影院`
- `source`:
  - `www.gamersky.com/wenku/movie`
- `target`: `/ent/movie`
### Rule 4
- `title`: `游观天下`
- `source`:
  - `www.gamersky.com/ent/discovery`
- `target`: `/ent/discovery`
### Rule 5
- `title`: `壁纸图库`
- `source`:
  - `www.gamersky.com/ent/wp`
- `target`: `/ent/wp`
### Rule 6
- `title`: `游民盘点`
- `source`:
  - `www.gamersky.com/wenku`
- `target`: `/ent/wenku`
### Rule 7
- `title`: `游民福利`
- `source`:
  - `www.gamersky.com/ent/xz`
- `target`: `/ent/xz`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "|all|qw|movie|discovery|wp|wenku|xz|\n|---|---|---|---|---|---|---|\n|热点图文|趣囧时间|游民影院|游观天下|壁纸图库|游民盘点|游民福利|\n",
  "example": "/gamersky/ent/xz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "ent.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "娱乐",
  "parameters": {
    "type": "分类类型，留空为 `all`"
  },
  "path": "/ent/:category?",
  "radar": [
    {
      "source": [
        "www.gamersky.com/ent"
      ],
      "target": "/ent/all",
      "title": "热点图文"
    },
    {
      "source": [
        "www.gamersky.com/ent/qw"
      ],
      "target": "/ent/qw",
      "title": "趣囧时间"
    },
    {
      "source": [
        "www.gamersky.com/wenku/movie"
      ],
      "target": "/ent/movie",
      "title": "游民影院"
    },
    {
      "source": [
        "www.gamersky.com/ent/discovery"
      ],
      "target": "/ent/discovery",
      "title": "游观天下"
    },
    {
      "source": [
        "www.gamersky.com/ent/wp"
      ],
      "target": "/ent/wp",
      "title": "壁纸图库"
    },
    {
      "source": [
        "www.gamersky.com/wenku"
      ],
      "target": "/ent/wenku",
      "title": "游民盘点"
    },
    {
      "source": [
        "www.gamersky.com/ent/xz"
      ],
      "target": "/ent/xz",
      "title": "游民福利"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "热点图文 - 游民娱乐 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73637415277299712",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.gamersky.com/ent",
      "title": "热点图文 - 游民娱乐",
      "type": "feed",
      "url": "rsshub://gamersky/ent"
    },
    {
      "description": null,
      "errorAt": "2025-08-14T15:44:50.225Z",
      "errorMessage": "Invalid type: ymfl\n",
      "id": "178823201593052164",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://gamersky/ent/ymfl"
    }
  ]
}
```
