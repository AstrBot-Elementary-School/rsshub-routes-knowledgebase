# Metacritic - Games

## Coverage
`index-only`

## Route
- Namespace: `metacritic`
- Namespace Name: `Metacritic`
- Route Path: `/metacritic/game/:sort?/:filter?`
- Route Name: `Games`
- Example: `/metacritic/game`
- URL: `metacritic.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `HenryQW, nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
| Metascore | User Score | Most Popular | Newest Releases |
| --------- | ---------- | ------------ | --------------- |
| metascore | userscore  | popular      | new             |

::: tip
The Filter parameter comes from the corresponding page URL. The following is an example:

The URL of [Action Games to Play on PS5](https://www.metacritic.com/browse/game/all/all/all-time/new/?platform=ps5\&genre=action) is `https://www.metacritic.com/browse/game/all/all/all-time/new/?platform=ps5&genre=action`. The Filter parameter is `platform=ps5&genre=action` and the route is [`/metacritic/game/new/platform=ps5&genre=action`](https://rsshub.app/metacritic/game/new/platform=ps5\&genre=action)
:::

## Parameters
- `sort`: Sort, see below, `new` for Newest Releases by default
- `filter`: Filter


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `metacritic.com/browse/game/*`
- `target`: `/game`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| Metascore | User Score | Most Popular | Newest Releases |\n| --------- | ---------- | ------------ | --------------- |\n| metascore | userscore  | popular      | new             |\n\n::: tip\nThe Filter parameter comes from the corresponding page URL. The following is an example:\n\nThe URL of [Action Games to Play on PS5](https://www.metacritic.com/browse/game/all/all/all-time/new/?platform=ps5\\&genre=action) is `https://www.metacritic.com/browse/game/all/all/all-time/new/?platform=ps5&genre=action`. The Filter parameter is `platform=ps5&genre=action` and the route is [`/metacritic/game/new/platform=ps5&genre=action`](https://rsshub.app/metacritic/game/new/platform=ps5\\&genre=action)\n:::",
  "example": "/metacritic/game",
  "heat": 0,
  "location": "index.tsx",
  "maintainers": [
    "HenryQW",
    "nczitzk"
  ],
  "name": "Games",
  "parameters": {
    "filter": "Filter",
    "sort": "Sort, see below, `new` for Newest Releases by default"
  },
  "path": "/game/:sort?/:filter?",
  "radar": [
    {
      "source": [
        "metacritic.com/browse/game/*"
      ],
      "target": "/game"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
