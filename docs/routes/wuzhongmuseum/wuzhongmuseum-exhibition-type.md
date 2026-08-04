# Museum of Wu - Exhibition

## Coverage
`index-only`

## Route
- Namespace: `wuzhongmuseum`
- Namespace Name: `Museum of Wu`
- Route Path: `/wuzhongmuseum/exhibition/:type?`
- Route Name: `Exhibition`
- Example: `/wuzhongmuseum/exhibition`
- URL: `www.wuzhongmuseum.com`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `exhibition.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Exhibition type, supported values: short (特别展览), long (常设展览), online (线上展览). Default: all exhibitions.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.wuzhongmuseum.com/portal/exhibition`
- `target`: `/exhibition`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/wuzhongmuseum/exhibition",
  "heat": 0,
  "location": "exhibition.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Exhibition",
  "parameters": {
    "type": "Exhibition type, supported values: short (特别展览), long (常设展览), online (线上展览). Default: all exhibitions."
  },
  "path": "/exhibition/:type?",
  "radar": [
    {
      "source": [
        "www.wuzhongmuseum.com/portal/exhibition"
      ],
      "target": "/exhibition"
    }
  ],
  "topFeeds": []
}
```
