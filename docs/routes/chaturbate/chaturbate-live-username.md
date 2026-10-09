# Chaturbate - Live status

## Coverage
`index-only`

## Route
- Namespace: `chaturbate`
- Namespace Name: `Chaturbate`
- Route Path: `/chaturbate/live/:username`
- Route Name: `Live status`
- Example: `/chaturbate/live/nakedbakers`
- URL: `chaturbate.com`
- Language: `_None_`
- Categories: `live`
- Maintainers: `DIYgod`
- Source Location: `live.ts`
- Source Module: `_None_`

## Description
Reports public live streams using the actual broadcast start time as the entry ID and publication date. When the room is offline or not public, it returns a status entry with a fixed ID and no publication date, so polling does not create new notifications. Only stream status and viewer counts are included.

## Parameters
- `username`: The broadcaster username from the room URL.


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `chaturbate.com/:username`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "description": "Reports public live streams using the actual broadcast start time as the entry ID and publication date. When the room is offline or not public, it returns a status entry with a fixed ID and no publication date, so polling does not create new notifications. Only stream status and viewer counts are included.",
  "example": "/chaturbate/live/nakedbakers",
  "features": {
    "nsfw": true
  },
  "heat": 0,
  "location": "live.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Live status",
  "parameters": {
    "username": "The broadcaster username from the room URL."
  },
  "path": "/live/:username",
  "radar": [
    {
      "source": [
        "chaturbate.com/:username"
      ]
    }
  ],
  "topFeeds": []
}
```
