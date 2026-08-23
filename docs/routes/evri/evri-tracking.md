# Evri - Parcel Tracking

## Coverage
`index-only`

## Route
- Namespace: `evri`
- Namespace Name: `Evri`
- Route Path: `/evri/:tracking`
- Route Name: `Parcel Tracking`
- Example: `/evri/H04AQA0004726589`
- URL: `www.evri.com/track-a-parcel`
- Language: `_None_`
- Categories: `other`
- Maintainers: `HenryQW`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tracking`: Tracking number


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.evri.com/track/parcel/:tracking/details`
- `target`: `/:tracking`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/evri/H04AQA0004726589",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "Parcel Tracking",
  "parameters": {
    "tracking": "Tracking number"
  },
  "path": "/:tracking",
  "radar": [
    {
      "source": [
        "www.evri.com/track/parcel/:tracking/details"
      ],
      "target": "/:tracking"
    }
  ],
  "topFeeds": [],
  "url": "www.evri.com/track-a-parcel"
}
```
