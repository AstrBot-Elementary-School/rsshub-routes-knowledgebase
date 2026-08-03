# Pikabu - User

## Coverage
`index-only`

## Route
- Namespace: `pikabu`
- Namespace Name: `Pikabu`
- Route Path: `/pikabu/user/:name`
- Route Name: `User`
- Example: `/pikabu/user/@bula.dragon`
- URL: `pikabu.ru`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: User name


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
  - `pikabu.ru/:name`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/pikabu/user/@bula.dragon",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "User",
  "parameters": {
    "name": "User name"
  },
  "path": "/user/:name",
  "radar": [
    {
      "source": [
        "pikabu.ru/:name"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
