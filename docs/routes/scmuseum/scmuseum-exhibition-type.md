# Sichuan Museum - Exhibition

## Coverage
`index-only`

## Route
- Namespace: `scmuseum`
- Namespace Name: `Sichuan Museum`
- Route Path: `/scmuseum/exhibition/:type?`
- Route Name: `Exhibition`
- Example: `/scmuseum/exhibition/temp`
- URL: `www.scmuseum.cn`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `exhibition.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Exhibition type, supported values: base (常设展览) or temp (临时展览), default is all exhibitions.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.scmuseum.cn/Visit/Exhibition`
- `target`: `/exhibition`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/scmuseum/exhibition/temp",
  "heat": 0,
  "location": "exhibition.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Exhibition",
  "parameters": {
    "type": "Exhibition type, supported values: base (常设展览) or temp (临时展览), default is all exhibitions."
  },
  "path": "/exhibition/:type?",
  "radar": [
    {
      "source": [
        "www.scmuseum.cn/Visit/Exhibition"
      ],
      "target": "/exhibition"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
