# itch.io - Browse

## Coverage
`index-only`

## Route
- Namespace: `itch`
- Namespace Name: `itch.io`
- Route Path: `/itch/:path{.+}?`
- Route Name: `Browse`
- Example: `/itch/games/new-and-popular/featured`
- URL: `itch.io`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
The path is the field after `itch.io` in the URL of the corresponding page, e.g. the URL of [Top Rated Games tagged Singleplayer](https://itch.io/games/top-rated/tag-singleplayer) is `https://itch.io/games/top-rated/tag-singleplayer`, where the field after `itch.io` is `/games/top-rated/tag-singleplayer`.

So the route is [`/itch/games/top-rated/tag-singleplayer`](https://rsshub.app/itch/games/top-rated/tag-singleplayer).

::: tip
You can browse all the tags [here](https://itch.io/tags).
:::

## Parameters
- `path`: Params


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "The path is the field after `itch.io` in the URL of the corresponding page, e.g. the URL of [Top Rated Games tagged Singleplayer](https://itch.io/games/top-rated/tag-singleplayer) is `https://itch.io/games/top-rated/tag-singleplayer`, where the field after `itch.io` is `/games/top-rated/tag-singleplayer`.\n\nSo the route is [`/itch/games/top-rated/tag-singleplayer`](https://rsshub.app/itch/games/top-rated/tag-singleplayer).\n\n::: tip\nYou can browse all the tags [here](https://itch.io/tags).\n:::",
  "example": "/itch/games/new-and-popular/featured",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Browse",
  "parameters": {
    "path": "Params"
  },
  "path": "/:path{.+}?",
  "topFeeds": []
}
```
