# YouTube - Shows

## Coverage
`index-only`

## Route
- Namespace: `youtube`
- Namespace Name: `YouTube`
- Route Path: `/youtube/shows/:username`
- Route Name: `Shows`
- Example: `/youtube/shows/@LinusTechTips`
- URL: `youtube.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `shows.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: YouTube handle or channel id


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.youtube.com/:username/shows`
  - `www.youtube.com/channel/:username/shows`
- `target`: `/shows/:username`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/youtube/shows/@LinusTechTips",
  "heat": 0,
  "location": "shows.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Shows",
  "parameters": {
    "username": "YouTube handle or channel id"
  },
  "path": "/shows/:username",
  "radar": [
    {
      "source": [
        "www.youtube.com/:username/shows",
        "www.youtube.com/channel/:username/shows"
      ],
      "target": "/shows/:username"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
