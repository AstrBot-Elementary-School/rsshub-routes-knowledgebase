# LowEndTalk - Discussion

## Coverage
`index-only`

## Route
- Namespace: `lowendtalk`
- Namespace Name: `LowEndTalk`
- Route Path: `/lowendtalk/discussion/:id`
- Route Name: `Discussion`
- Example: `/lowendtalk/discussion/168480`
- URL: `lowendtalk.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `discussion.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Discussion id, can be found in the URL


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `lowendtalk.com/discussion/:id/*`
  - `lowendtalk.com/discussion/:id`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/lowendtalk/discussion/168480",
  "heat": 0,
  "location": "discussion.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Discussion",
  "parameters": {
    "id": "Discussion id, can be found in the URL"
  },
  "path": "/discussion/:id",
  "radar": [
    {
      "source": [
        "lowendtalk.com/discussion/:id/*",
        "lowendtalk.com/discussion/:id"
      ]
    }
  ],
  "topFeeds": [],
  "url": "lowendtalk.com"
}
```
