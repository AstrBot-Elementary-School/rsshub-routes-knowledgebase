# JAVLibrary - Best Rated Videos

## Coverage
`index-only`

## Route
- Namespace: `javlibrary`
- Namespace Name: `JAVLibrary`
- Route Path: `/javlibrary/videos/bestrated/:language?/:mode?`
- Route Name: `Best Rated Videos`
- Example: `/javlibrary/bestrated/en`
- URL: `javlibrary.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `bestrated.ts`
- Source Module: `_None_`

## Description
| Last Month | All Time |
| ---------- | -------- |
| 1          | 2        |

## Parameters
- `language`: Language, see below, Japanese by default, as `ja`
- `mode`: Mode, see below, Last Month by default, as `1`


## Features
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "| Last Month | All Time |\n| ---------- | -------- |\n| 1          | 2        |",
  "example": "/javlibrary/bestrated/en",
  "features": {
    "nsfw": true
  },
  "heat": 1,
  "location": "bestrated.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Best Rated Videos",
  "parameters": {
    "language": "Language, see below, Japanese by default, as `ja`",
    "mode": "Mode, see below, Last Month by default, as `1`"
  },
  "path": [
    "/videos/bestrated/:language?/:mode?",
    "/bestrated/:language?/:mode?"
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
