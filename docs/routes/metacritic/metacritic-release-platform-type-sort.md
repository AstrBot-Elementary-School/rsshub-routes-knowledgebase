# Metacritic - Game Releases

## Coverage
`index-only`

## Route
- Namespace: `metacritic`
- Namespace Name: `Metacritic`
- Route Path: `/metacritic/release/:platform/:type?/:sort?`
- Route Name: `Game Releases`
- Example: `/metacritic/release/nintendo-switch/coming`
- URL: `metacritic.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `HenryQW`
- Source Location: `release.ts`
- Source Module: `_None_`

## Description
Platforms supported:

| PS5 | Xbox Series X | Switch 2          | Switch          | PC | Mobile | Meta Quest | PS4 | Xbox One | Wii U | 3DS | PS Vita |
| --- | ------------- | ----------------- | --------------- | -- | ------ | ---------- | --- | -------- | ----- | --- | ------- |
| ps5 | xbox-series-x | nintendo-switch-2 | nintendo-switch | pc | mobile | meta-quest | ps4 | xbox-one | wii-u | 3ds | ps-vita |

Release types, default to `new`:

| New Releases | Coming Soon |
| ------------ | ----------- |
| new          | coming      |

Sorting types, default to `date`:

| Date | Metacritic Score | User Score |
| ---- | ---------------- | ---------- |
| date | metascore        | userscore  |

## Parameters
- `platform`: console platform, see below, `all` for every platform
- `type`: release type, default to `new`
- `sort`: sorting type, default to `date`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `metacritic.com/browse/game/:platform`
- `target`: `/release/:platform`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "Platforms supported:\n\n| PS5 | Xbox Series X | Switch 2          | Switch          | PC | Mobile | Meta Quest | PS4 | Xbox One | Wii U | 3DS | PS Vita |\n| --- | ------------- | ----------------- | --------------- | -- | ------ | ---------- | --- | -------- | ----- | --- | ------- |\n| ps5 | xbox-series-x | nintendo-switch-2 | nintendo-switch | pc | mobile | meta-quest | ps4 | xbox-one | wii-u | 3ds | ps-vita |\n\nRelease types, default to `new`:\n\n| New Releases | Coming Soon |\n| ------------ | ----------- |\n| new          | coming      |\n\nSorting types, default to `date`:\n\n| Date | Metacritic Score | User Score |\n| ---- | ---------------- | ---------- |\n| date | metascore        | userscore  |",
  "example": "/metacritic/release/nintendo-switch/coming",
  "heat": 0,
  "location": "release.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "Game Releases",
  "parameters": {
    "platform": "console platform, see below, `all` for every platform",
    "sort": "sorting type, default to `date`",
    "type": "release type, default to `new`"
  },
  "path": "/release/:platform/:type?/:sort?",
  "radar": [
    {
      "source": [
        "metacritic.com/browse/game/:platform"
      ],
      "target": "/release/:platform"
    }
  ],
  "topFeeds": []
}
```
