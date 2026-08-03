# U.S. Food and Drug Administration - CDRHNew

## Coverage
`index-only`

## Route
- Namespace: `fda`
- Namespace Name: `U.S. Food and Drug Administration`
- Route Path: `/fda/cdrh/:titleOnly?`
- Route Name: `CDRHNew`
- Example: `/fda/cdrh`
- URL: `fda.gov/medical-devices/news-events-medical-devices/cdrhnew-news-and-updates`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `cdrh.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `titleOnly`: Title only, empty by default which includes the full text, any other value shows the title only


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `fda.gov/medical-devices/news-events-medical-devices/cdrhnew-news-and-updates`
  - `fda.gov/`
- `target`: `/cdrh/:titleOnly`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/fda/cdrh",
  "heat": 0,
  "location": "cdrh.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "CDRHNew",
  "parameters": {
    "titleOnly": "Title only, empty by default which includes the full text, any other value shows the title only"
  },
  "path": "/cdrh/:titleOnly?",
  "radar": [
    {
      "source": [
        "fda.gov/medical-devices/news-events-medical-devices/cdrhnew-news-and-updates",
        "fda.gov/"
      ],
      "target": "/cdrh/:titleOnly"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "fda.gov/medical-devices/news-events-medical-devices/cdrhnew-news-and-updates"
}
```
