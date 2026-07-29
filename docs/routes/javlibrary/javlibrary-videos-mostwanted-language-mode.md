# JAVLibrary - Most Wanted Videos

## Coverage
`index-only`

## Route
- Namespace: `javlibrary`
- Namespace Name: `JAVLibrary`
- Route Path: `/javlibrary/videos/mostwanted/:language?/:mode?`
- Route Name: `Most Wanted Videos`
- Example: `/javlibrary/mostwanted/en`
- URL: `javlibrary.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `mostwanted.ts`
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
  "example": "/javlibrary/mostwanted/en",
  "features": {
    "nsfw": true
  },
  "heat": 0,
  "location": "mostwanted.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Most Wanted Videos",
  "parameters": {
    "language": "Language, see below, Japanese by default, as `ja`",
    "mode": "Mode, see below, Last Month by default, as `1`"
  },
  "path": [
    "/videos/mostwanted/:language?/:mode?",
    "/mostwanted/:language?/:mode?"
  ],
  "topFeeds": []
}
```
