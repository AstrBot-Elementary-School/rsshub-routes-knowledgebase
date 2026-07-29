# JAVLibrary - Videos by user

## Coverage
`index-only`

## Route
- Namespace: `javlibrary`
- Namespace Name: `JAVLibrary`
- Route Path: `/javlibrary/users/:id/:type/:language?`
- Route Name: `Videos by user`
- Example: `/javlibrary/userwatched/mangudai/en`
- URL: `javlibrary.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk, DIYgod, junfengP`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
| Wanted     | Watched     | Owned     |
| ---------- | ----------- | --------- |
| userwanted | userwatched | userowned |

## Parameters
- `type`: Type, see below
- `id`: User id, can be found in URL
- `language`: Language, see below, Japanese by default, as `ja`


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
  "description": "| Wanted     | Watched     | Owned     |\n| ---------- | ----------- | --------- |\n| userwanted | userwatched | userowned |",
  "example": "/javlibrary/userwatched/mangudai/en",
  "features": {
    "nsfw": true
  },
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "nczitzk",
    "DIYgod",
    "junfengP"
  ],
  "name": "Videos by user",
  "parameters": {
    "id": "User id, can be found in URL",
    "language": "Language, see below, Japanese by default, as `ja`",
    "type": "Type, see below"
  },
  "path": [
    "/users/:id/:type/:language?",
    "/:type/:id/:language?"
  ],
  "topFeeds": []
}
```
