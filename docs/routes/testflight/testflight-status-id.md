# TestFlight - Beta availability

## Coverage
`index-only`

## Route
- Namespace: `testflight`
- Namespace Name: `TestFlight`
- Route Path: `/testflight/status/:id`
- Route Name: `Beta availability`
- Example: `/testflight/status/tLcYLZJV`
- URL: `testflight.apple.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `DIYgod`
- Source Location: `status.ts`
- Source Module: `_None_`

## Description
Reports the current public beta availability. The item GUID changes when the status changes. Apple does not expose the exact number of remaining slots.

## Parameters
- `id`: Public invitation ID from https://testflight.apple.com/join/ID.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `testflight.apple.com/join/:id`
- `target`: `/status/:id`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "Reports the current public beta availability. The item GUID changes when the status changes. Apple does not expose the exact number of remaining slots.",
  "example": "/testflight/status/tLcYLZJV",
  "heat": 0,
  "location": "status.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Beta availability",
  "parameters": {
    "id": "Public invitation ID from https://testflight.apple.com/join/ID."
  },
  "path": "/status/:id",
  "radar": [
    {
      "source": [
        "testflight.apple.com/join/:id"
      ],
      "target": "/status/:id"
    }
  ],
  "topFeeds": []
}
```
