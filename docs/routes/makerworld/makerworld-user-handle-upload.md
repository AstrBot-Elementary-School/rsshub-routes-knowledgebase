# MakerWorld - User Uploads

## Coverage
`index-only`

## Route
- Namespace: `makerworld`
- Namespace Name: `MakerWorld`
- Route Path: `/makerworld/user/:handle/upload`
- Route Name: `User Uploads`
- Example: `/makerworld/user/@Wcad00/upload`
- URL: `makerworld.com`
- Language: `_None_`
- Categories: `design`
- Maintainers: `TonyRL`
- Source Location: `user-upload.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `handle`: User handle


## Features
- `requirePuppeteer`: true

## Radar
### Rule 1
- `source`:
  - `makerworld.com/:lang/:handle/upload`
  - `makerworld.com/:lang/:handle`

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "example": "/makerworld/user/@Wcad00/upload",
  "features": {
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "user-upload.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "User Uploads",
  "parameters": {
    "handle": "User handle"
  },
  "path": "/user/:handle/upload",
  "radar": [
    {
      "source": [
        "makerworld.com/:lang/:handle/upload",
        "makerworld.com/:lang/:handle"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
