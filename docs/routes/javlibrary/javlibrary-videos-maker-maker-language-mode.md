# JAVLibrary - Videos by makers

## Coverage
`index-only`

## Route
- Namespace: `javlibrary`
- Namespace Name: `JAVLibrary`
- Route Path: `/javlibrary/videos/maker/:maker?/:language?/:mode?`
- Route Name: `Videos by makers`
- Example: `/javlibrary/videos/maker/arlq/cn`
- URL: `javlibrary.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `Huzhixin00`
- Source Location: `maker.ts`
- Source Module: `_None_`

## Description
| videos with comments (by date) | everything (by date) |
| ------------------------------ | -------------------- |
| 1                              | 2                    |

## Parameters
- `maker`: Maker, S1 NO.1 STYLE by default, as `arlq`
- `language`: Language, see below, Japanese by default, as `ja`
- `mode`: Mode, see below, videos with comments (by date) by default, as `1`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "| videos with comments (by date) | everything (by date) |\n| ------------------------------ | -------------------- |\n| 1                              | 2                    |",
  "example": "/javlibrary/videos/maker/arlq/cn",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "maker.ts",
  "maintainers": [
    "Huzhixin00"
  ],
  "name": "Videos by makers",
  "parameters": {
    "language": "Language, see below, Japanese by default, as `ja`",
    "maker": "Maker, S1 NO.1 STYLE by default, as `arlq`",
    "mode": "Mode, see below, videos with comments (by date) by default, as `1`"
  },
  "path": "/videos/maker/:maker?/:language?/:mode?",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
