# Trakt.tv - User favorites

## Coverage
`index-only`

## Route
- Namespace: `trakt`
- Namespace Name: `Trakt.tv`
- Route Path: `/trakt/collection/:username`
- Route Name: `User favorites`
- Example: `/trakt/collection/sonply`
- URL: `trakt.tv`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `hoilc`
- Source Location: `collection.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: Username


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `app.trakt.tv/profile/:username`
- `target`: `/collection/:username`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/trakt/collection/sonply",
  "heat": 0,
  "location": "collection.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "User favorites",
  "parameters": {
    "username": "Username"
  },
  "path": "/collection/:username",
  "radar": [
    {
      "source": [
        "app.trakt.tv/profile/:username"
      ],
      "target": "/collection/:username"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
