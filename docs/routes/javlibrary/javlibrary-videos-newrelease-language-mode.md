# JAVLibrary - New Releases

## Coverage
`index-only`

## Route
- Namespace: `javlibrary`
- Namespace Name: `JAVLibrary`
- Route Path: `/javlibrary/videos/newrelease/:language?/:mode?`
- Route Name: `New Releases`
- Example: `/javlibrary/newrelease/en`
- URL: `javlibrary.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `newrelease.ts`
- Source Module: `_None_`

## Description
| videos with comments (by date) | everything (by date) |
| ------------------------------ | -------------------- |
| 1                              | 2                    |

## Parameters
- `language`: Language, see below, Japanese by default, as `ja`
- `mode`: Mode, see below, videos with comments (by date) by default, as `1`


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
  "description": "| videos with comments (by date) | everything (by date) |\n| ------------------------------ | -------------------- |\n| 1                              | 2                    |",
  "example": "/javlibrary/newrelease/en",
  "features": {
    "nsfw": true
  },
  "heat": 2,
  "location": "newrelease.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "New Releases",
  "parameters": {
    "language": "Language, see below, Japanese by default, as `ja`",
    "mode": "Mode, see below, videos with comments (by date) by default, as `1`"
  },
  "path": [
    "/videos/newrelease/:language?/:mode?",
    "/newrelease/:language?/:mode?"
  ],
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-06-08T19:57:07.358Z",
      "errorMessage": "[GET] \"https://www.javlibrary.com/ja/vl_newrelease.php?list&mode=1\": 403 Forbidden\n",
      "id": "154611732349321216",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://javlibrary/videos/newrelease"
    }
  ]
}
```
