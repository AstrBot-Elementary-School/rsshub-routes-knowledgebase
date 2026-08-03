# Metacritic - TV Shows

## Coverage
`index-only`

## Route
- Namespace: `metacritic`
- Namespace Name: `Metacritic`
- Route Path: `/metacritic/tv/:sort?/:filter?`
- Route Name: `TV Shows`
- Example: `/metacritic/tv`
- URL: `metacritic.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `tv.ts`
- Source Module: `_None_`

## Description
| Metascore | User Score | Most Popular | Newest Releases |
| --------- | ---------- | ------------ | --------------- |
| metascore | userscore  | popular      | new             |

::: tip
The Filter parameter comes from the corresponding page URL. The following is an example:

The URL of [Documentary TV Shows to Watch on Prime Video](https://www.metacritic.com/browse/tv/all/all/all-time/new/?network=prime-video\&genre=documentary) is `https://www.metacritic.com/browse/tv/all/all/all-time/new/?network=prime-video&genre=documentary`. The Filter parameter is `network=prime-video&genre=documentary` and the route is [`/metacritic/tv/new/network=prime-video&genre=documentary`](https://rsshub.app/metacritic/tv/new/network=prime-video\&genre=documentary)
:::

## Parameters
- `sort`: Sort, see below, `new` for Newest Releases by default
- `filter`: Filter


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `metacritic.com/browse/tv/*`
- `target`: `/tv`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| Metascore | User Score | Most Popular | Newest Releases |\n| --------- | ---------- | ------------ | --------------- |\n| metascore | userscore  | popular      | new             |\n\n::: tip\nThe Filter parameter comes from the corresponding page URL. The following is an example:\n\nThe URL of [Documentary TV Shows to Watch on Prime Video](https://www.metacritic.com/browse/tv/all/all/all-time/new/?network=prime-video\\&genre=documentary) is `https://www.metacritic.com/browse/tv/all/all/all-time/new/?network=prime-video&genre=documentary`. The Filter parameter is `network=prime-video&genre=documentary` and the route is [`/metacritic/tv/new/network=prime-video&genre=documentary`](https://rsshub.app/metacritic/tv/new/network=prime-video\\&genre=documentary)\n:::",
  "example": "/metacritic/tv",
  "heat": 0,
  "location": "tv.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "TV Shows",
  "parameters": {
    "filter": "Filter",
    "sort": "Sort, see below, `new` for Newest Releases by default"
  },
  "path": "/tv/:sort?/:filter?",
  "radar": [
    {
      "source": [
        "metacritic.com/browse/tv/*"
      ],
      "target": "/tv"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
